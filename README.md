# NumPy Practice — AI/ML Foundation

Personal NumPy practice exercises built as part of an AI/ML learning roadmap.
Each question is framed around real ML concepts to build practical intuition.

---

## Topics Covered

| # | Topic | ML Concept |
|---|-------|------------|
| Q1 | Array creation, `arange`, `shape` | Data representation |
| Q2 | Reshape 1D → 2D | Samples × Features matrix |
| Q3 | Chained reshape | Weight matrix initialization |
| Q4 | Multiple reshapes | Image pixel manipulation |
| Q5 | Slicing, boolean indexing | Data filtering, outlier removal |
| Q6 | `axis` operations — mean, max | Per-sample / per-feature stats |
| Q7 | Boolean replacement | Data cleaning, corrupt value removal |
| Q8 | `np.where`, grade classifier | Label generation (`y_train`) |
| Q9 | `argmax`, `argwhere`, normalization | Feature scaling (Min-Max) |

---

## Key Concepts

- **Boolean Indexing** — `arr[arr > value]` filters values directly
- **np.where** — assigns labels based on condition: `np.where(condition, "Pass", "Fail")`
- **axis=0 vs axis=1** — column-wise vs row-wise operations
- **Normalization** — `(x - min) / (max - min)` scales values between 0 and 1
- **argmax + unravel_index** — finds position of max value in 2D array

---

## How to Run

```bash
pip install numpy
python numpy_practice.py
```

---

## Learning Roadmap

```
NumPy ✅ → Pandas → Matplotlib → Scikit-learn → ML Projects
```
