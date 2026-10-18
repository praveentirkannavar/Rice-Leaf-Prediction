# Rice Leaf Disease Prediction 🌿

# Project Description

A Convolutional Neural Network (CNN) built with TensorFlow and Keras to classify rice leaf images into three disease classes. The project uses image preprocessing, data augmentation, dropout, and early stopping to help reduce overfitting.


# Technologies Used
- Python

- TensorFlow / Keras

- NumPy

- Matplotlib

- Jupyter Notebook


# Project Workflow
- Load rice leaf images from class-based folders.

- Resize images to 128 × 128 pixels and normalize pixel values.

- Apply data augmentation to training images.

- Train a CNN to classify three classes.

- Evaluate the model on validation data and visualize predictions.


# Dataset
The notebook describes a dataset of approximately 120 images across three classes. The dataset is not included in this repository; provide your own dataset arranged in separate folders for each class.


# Run the Project
- Install dependencies:

- pip install tensorflow numpy matplotlib jupyter

- Open RiceleafPred.ipynb in Jupyter Notebook or JupyterLab.

- Update dataset_path in the notebook to point to your dataset directory.

- Run the notebook cells in order.


# Notes
The dataset is small, so validation results may vary and overfitting is a risk. Data augmentation, dropout, and early stopping are used to improve generalization.

Repository Structure

Rice-Leaf-Disease-Prediction/
├── RiceleafPred.ipynb
└── README.md
