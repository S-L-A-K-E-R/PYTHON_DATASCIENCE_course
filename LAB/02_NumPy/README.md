# NumPy — short, progressive Colab notebooks

**Goal:** connect NumPy to the matrices students already use in mathematics, through small, achievable exercises.

| Step | Notebook | Open in Colab |
| --- | --- | --- |
| Guided introduction | [00 — NumPy quickstart](00_NumPy_Quickstart.ipynb) | [Open in Colab](https://colab.research.google.com/github/S-L-A-K-E-R/PYTHON_DATASCIENCE_course/blob/master/LAB/02_NumPy/00_NumPy_Quickstart.ipynb) |
| Lab 1 | [01 — Arrays and measurements](01_Arrays_and_Measurements.ipynb) | [Open in Colab](https://colab.research.google.com/github/S-L-A-K-E-R/PYTHON_DATASCIENCE_course/blob/master/LAB/02_NumPy/01_Arrays_and_Measurements.ipynb) |
| Lab 2 | [02 — Matrix applications](02_Matrix_Applications.ipynb) | [Open in Colab](https://colab.research.google.com/github/S-L-A-K-E-R/PYTHON_DATASCIENCE_course/blob/master/LAB/02_NumPy/02_Matrix_Applications.ipynb) |
| Lab 3 | [03 — 20 progressive exercises (★ to ★★)](03_NumPy_20_Exercises.ipynb) | [Open in Colab](https://colab.research.google.com/github/S-L-A-K-E-R/PYTHON_DATASCIENCE_course/blob/master/LAB/02_NumPy/03_NumPy_20_Exercises.ipynb) |

## Approach

1. **See the goal first:** each challenge shows its expected numerical result or chart.
2. **Investigate a small API:** the notebook links to the precise official reference or gives one small reminder.
3. **Write a small amount of code:** no external datasets, complex helper functions, or lengthy setup.
4. **Compare, explain, and save:** readable cells and a short reflection matter more than number of lines.

Labs are sequential but self-contained. Run their setup cells and work at your own pace. The optional visual tasks reuse the previous Matplotlib module and can be completed separately.

## Colab and local Python

**Google Colab:** click a link above, create a copy for editing, and run the cells top to bottom. Standard Colab includes NumPy and Matplotlib; there are no files to download.

**Local Jupyter / VS Code:** use a recent Python 3 version and install `numpy` (and `matplotlib` for the optional plots). Example: `python -m pip install numpy matplotlib`.

> The repository root `requirements.txt` is from the original handbook and pins old historical package versions; it is **not** needed for these new labs.

## References

- [NumPy: the absolute basics for beginners](https://numpy.org/doc/stable/user/absolute_beginners.html)
- [NumPy: indexing](https://numpy.org/doc/stable/user/basics.indexing.html)
- [NumPy: matrix multiplication / `@`](https://numpy.org/doc/stable/reference/generated/numpy.matmul.html)
- [Python Data Science Handbook reference notebooks](../../REFERENCES/02_NumPy/)

The quickstart and first two labs are original teaching exercises, inspired by the accompanying handbook references. **Lab 3** adapts 20 exercises from [Nicolas P. Rougier's numpy-100](https://github.com/rougier/numpy-100), with new settings, explicit targets and hints. The original collection is under the [MIT license](../../LICENSE-NUMPY-100).
