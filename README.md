
## 🧠 Perceptron Classifier from Scratch

This project demonstrates a simple implementation of a **Perceptron** — one of the earliest and most fundamental algorithms in machine learning — built from scratch using **NumPy** and **scikit-learn** for data generation and preprocessing.

---

### 📌 Features

* Custom Perceptron class with:

  * Weight initialization
  * Linear transformation
  * Heaviside step activation
  * Loss calculation and weight updates
* Uses `make_blobs()` for generating synthetic binary classification data
* Trains the perceptron over multiple epochs
* Visualizes prediction results using `matplotlib`

---

### 📁 Project Structure

```
Perceptron/
│
├── Perceptron.ipynb       # Jupyter notebook containing the full implementation
├── README.md              # Project documentation
```

---

### ⚙️ Requirements

* Python 3.7+
* NumPy
* scikit-learn
* matplotlib

Install dependencies using:

```bash
pip install numpy scikit-learn matplotlib
```

---

### 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/Perceptron.git
cd Perceptron
```

2. Open the notebook in Jupyter:

```bash
jupyter notebook Perceptron.ipynb
```

3. Run the cells to:

   * Generate and scale data
   * Train the perceptron
   * Visualize classification results

---

### 📊 Output

* Accuracy score on test data
* Scatter plot of the test dataset with predicted classes

---

### 📈 Sample Result

![image](https://github.com/user-attachments/assets/e0ca314d-f5e0-4137-adc6-6d1187cee8ff)

---

### 🤖 About the Perceptron

The perceptron is a binary classifier that linearly separates data using the rule:

$$
\text{output} = 
\begin{cases}
1 & \text{if } \mathbf{w} \cdot \mathbf{x} + b \geq 0 \\
0 & \text{otherwise}
\end{cases}
$$

---

### 📚 References

* [Scikit-learn Documentation](https://scikit-learn.org/)
* [Perceptron - Wikipedia](https://en.wikipedia.org/wiki/Perceptron)

---

### 🧑‍💻 Author

**Muhammad Imran**
Bachelor's in Artificial Intelligence — National University of Technology
GitHub: [@your-username](https://github.com/Imran-Codes07))

---
