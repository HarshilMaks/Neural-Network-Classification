# Neural Network Classification

## Overview

This project implements a multilayer neural network for classification tasks. The code is organized within a Jupyter Notebook (`code.ipynb`) and relies on helper functions defined in `helper_functions.py` to build, train, and evaluate the model.

---

## Features

- Data loading and preprocessing using NumPy and Pandas.
- Modular network construction with customizable layer sizes and activation functions via `helper_functions.py`.
- Training loop including forward and backward propagation and weight updates.
- Model evaluation with accuracy, loss curves, and confusion matrices.
- Visualization of training performance using Matplotlib.

---

## Dataset

- **Source:** Defined within the notebook (e.g., `helper_functions.load_data()`).
- **Description:** The dataset is loaded and split into training and testing sets. Replace the placeholder with the actual dataset name and details.

---

## Technology Stack

- **Programming Language:** Python
- **Libraries:**
  - NumPy
  - Pandas
  - Matplotlib
  - Scikit-learn (for data splitting and metrics)
  - Jupyter Notebook

---

## Results

- Achieved **99.62% accuracy** on the test set.  
- Training and validation loss curves illustrate the model's convergence.  
- Confusion matrix highlights classification performance across classes.

---

## Future Improvements

- Integrate additional activation functions and optimization algorithms.
- Extend to deeper architectures or convolutional layers for image data.
- Implement early stopping and learning rate schedules.
- Package the training and inference pipeline as a Python module.

---

## Acknowledgments

- Custom helper functions defined in `helper_functions.py` for network operations.
- Open-source libraries for data handling and visualization.

