# Handwritten Digit Recognition with MNIST Dataset

This project demonstrates the automatic recognition and interpretation of handwritten numbers using the MNIST dataset. The MNIST dataset consists of 70,000 images of handwritten digits, each with 784 features. The project applies Principal Component Analysis (PCA) for dimensionality reduction and Logistic Regression for classification.

## Project Structure

- `mnist_recognition.py`: Python script for the entire recognition pipeline, including data loading, preprocessing, PCA, and Logistic Regression.
- `README.md`: This file providing an overview and instructions.

## Dependencies

The project requires the following Python libraries:

- `pandas`
- `matplotlib`
- `scikit-learn`
- `numpy`
- `warnings`

Install these dependencies using `pip`:

```bash
pip install pandas matplotlib scikit-learn numpy
```

## Dataset
The dataset used is the MNIST handwritten digits dataset, which is available through the sklearn library.

## Results
The model achieved an accuracy of approximately 91.84% on the test set.

## Usage
To run the code, execute the mnist_recognition.py script. The script performs data loading, preprocessing, PCA, model training, and evaluation.
