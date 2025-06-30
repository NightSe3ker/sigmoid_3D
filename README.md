# 📈 3D Visualization of Sigmoid Function

This project demonstrates the 3D plotting of the **Sigmoid activation function**, which is widely used in neural networks and logistic regression. The visualization helps understand how input values and weights affect the sigmoid's output.

---

## ✅ What This Code Does

- Implements a generalized **sigmoid function**:  
  \[
  \sigma(z) = \frac{1}{1 + e^{-(w_1 x_1 + w_2 x_2 + b)}}
  \]
- Uses NumPy to generate a grid of `x1` and `x2` values.
- Calculates the sigmoid output `Z` for each `(x1, x2)` pair.
- Uses Matplotlib's 3D plotting toolkit to generate a **surface plot**.

---

## 📊 Output

The output is a **3D surface plot** that illustrates how the sigmoid function compresses input values into the `[0, 1]` range.

The plot shows:
- A gradual slope in the middle (non-linear region)
- Flattening out near 0 and 1 at extremes of input

---

## 🧰 Technologies Used

- Python
- NumPy
- Matplotlib
- mpl_toolkits.mplot3d
- Pandas (loaded but not used in visualization)

---

## 📋 Requirements

To run this notebook, install the required packages:

```bash
pip install numpy matplotlib pandas
