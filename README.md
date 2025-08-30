# PCA on MNIST Dataset 🎨🔢

This project applies **Principal Component Analysis (PCA)** to the MNIST dataset for dimensionality reduction and visualization.

Libraries:
  numpy
  pandas
  matplotlib
  scikit-learn

Steps:
  Load MNIST data from Kaggle Digit Recognizer dataset
  Understand dataset 
  Train the model without using PCA
  Train the model using PCA
  Perform PCA to reduce 784-dimensional data to 2D and 3D
  Visualize digit clusters in reduced space

## Results:
- PCA reduces computation time
- 2D and 3D PCA visualization shows digit clusters

## How to Run:
```bash
kaggle datasets download -d digit-recognizer
jupyter notebook PCA-on-MNIST.ipynb
