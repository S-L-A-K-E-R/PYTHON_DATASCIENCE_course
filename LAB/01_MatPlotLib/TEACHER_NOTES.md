# Instructor notes (keep separate from student handout)

## Intended learning experience

The scaffold runs the library imports and loads the datasets; students **write every plotting command**. Show each reference PNG and ask students to find **one Matplotlib mechanism at a time**. Exact pixel matching is unnecessary. Model answers should be demonstrated only after students have made their own attempt.

This adapts the scope, not the prose, of Jake VanderPlas's *Python Data Science Handbook* Ch. 4. Reference chapters on line/scatter plots, histograms, legends/colorbars, subplots, error bars, contours, and 3D surfaces are selected. The original book includes dated style names/backends; encourage **current Matplotlib documentation** instead.

## Pace

| Challenge | Suggested time | Core plotting skill | Handbook parallels |
| --- | ---: | --- | --- |
| 01 Air quality | 20 min | multiple lines, styles, threshold, legend | 04.01, 04.06 |
| 02 Model predictions | 25 min | scatter, continuous colors, colorbar, identity line | 04.02, 04.07 |
| 03 Distributions | 20 min | shared histogram bins, transparency, density | 04.05 |
| 04 Dashboard | 35 min | object-oriented Axes, 2×2 subplots, composition | 04.08, 04.11 |
| 05 Calibration | 20 min | error bars, annotation | 04.03, 04.09 |
| 06 Heatmap | 25 min | image matrix, extent, origin, colorbar | 04.04, 04.07 |
| 07 Contour lines | 30 min | filled contours, labelled isolines | 04.04 |
| 08 3D landscape | 30 min | 3D axes, surface, viewpoint | 04.12 |

Session 1: 100 min challenges + ~20 min for discussion, help, and review. Session 2: 105 min challenges + ~15 min wrap-up. Target minutes are estimates, not time limits.

## How to nudge without giving answers

- First hint: ask which **plot family** students see, what data maps to x/y/color/size, and whether they need **one or many Axes**.
- Second hint: point them to a specific **Matplotlib gallery category** or the corresponding handbook chapter.
- Third hint: give a single keyword (e.g., "colorbar", "extent", "errorbar", "contourf", "view_init") and ask them to read its official reference and prototype a tiny example.
- Avoid pasting complete solution code or requiring students to exactly match color values.

## Suggested review checklist (20 points)

| Criterion | Points |
| --- | ---: |
| Correct data-to-visual encoding and plot type | 8 |
| Labels, units, legend, scales, colorbars, error bars when specified | 5 |
| Figure composition and readability | 3 |
| Reproducibility: clean restart + Run All, no broken imports | 2 |
| Reflection and explanation of one discovered mechanism | 2 |

Give completion/partial credit rather than a pixel-difference score. Encourage students to justify changes that improve accessibility (e.g. color choices, labels).

## Operational notes

- Data are **artificial**, generated from fixed random seeds. They are not actual station readings, ground truth model studies, or building-safety measurements.
- The 25 µg/m³ line in #01 is an illustrative *classroom reference*, not a declared regulatory threshold.
- #05 uncertainties are ±1 standard deviation, **not** 95% confidence intervals.
- Student notebooks deliberately use NumPy arrays and avoid Pandas or scikit-learn (planned future chapters).
- The goal images are source of *appearance*, not solutions; a future instructor-only solution notebook could be maintained separately if needed.
