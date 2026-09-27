# Machine Learning Algorithms from Scratch

This repository contains pure Python implementations of foundational Machine Learning algorithms built entirely from scratch. 

Rather than relying on high-level, optimized libraries like `scikit-learn` or `TensorFlow`, every algorithm here is constructed using only the standard math library, `numpy` for matrix operations, and `pandas` for data manipulation. The goal of this project is to demystify the "black box" of machine learning and translate raw calculus, linear algebra, and probability theory into functional, optimized code.

## Core Philosophy
Using `.fit()` and `.predict()` is easy. Understanding the exact calculus behind a backpropagated gradient, the logic of a recursive greedy split, or the array manipulation required to perfectly stratify a highly imbalanced dataset is hard. 

This repository serves as a transparent, mathematically rigorous exploration of how these algorithms actually learn.

## Technology Stack
* **Python 3.x**
* **NumPy:** Used for vectorized matrix dot products, array manipulations, and avoiding slow native Python `for` loops.
* **Pandas:** Used strictly for initial data loading, feature isolation, and structural dataset management.
* **Math:** Used for raw logarithmic functions, exponentials, and combinatorial math.


## How to Navigate This Repository

Each algorithm is housed in its own directory containing:
1. **The Core Algorithm:** The pure Python `.py` file containing the math, the training loops, and the prediction logic.
2. **The Test Script:** An execution script demonstrating how to instantiate the model, pass it a dataset, and evaluate the results using the custom Cross-Validation pipeline.
3. **Datasets:** The raw `.csv` files (e.g., Wine Quality, Play Tennis) used to train and test the models.

### Running the Code
Because this project avoids heavy ML frameworks, running the models requires minimal setup. Simply clone the repository and ensure you have `numpy` and `pandas` installed in your environment.

```bash
git clone [https://github.com/yourusername/ml-from-scratch.git](https://github.com/yourusername/ml-from-scratch.git)
cd ml-from-scratch
pip install numpy pandas
