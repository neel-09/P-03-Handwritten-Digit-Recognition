## Handwritten Digit Recognition

*A machine learning project that classifies handwritten digits from the MNIST dataset.*

# 1. Project Overview

This project focuses on the classic machine learning problem of recognizing handwritten digits. It uses the well-known MNIST dataset, a large collection of handwritten digits (0-9). The goal is to build and train a model that can accurately classify a given image of a digit into its correct numerical category.

# 2. Dataset

The MNIST dataset consists of 70,000 images of handwritten digits.

*Images:* Each image is a grayscale image with a resolution of 28x28 pixels.

*Classes:* There are 10 classes, one for each digit from 0 to 9.

The dataset is typically split into 60,000 training images and 10,000 testing images.

# 3. Methodology

The project follows a standard deep learning workflow for image classification:

**Data Preprocessing:** Images are flattened and normalized to scale the pixel values.

**Model Architecture:** A Neural Network (or a Convolutional Neural Network) is designed using the **Keras** API.

**Model Training:** The model is trained on the preprocessed training data using **TensorFlow**.

**Model Evaluation:** The model's performance is measured using **accuracy** and a **confusion matrix** on the test set.


# 4. Results

The trained classifier is able to achieve a high level of accuracy in recognizing handwritten digits.
**Accuracy: 97.54%**
Interpretation: This represents the percentage of digits that our model correctly classified on the test set.

# 5. Technologies Used

Python
NumPy
Matplotlib(for visualization)
Tenserflow,Keras

# 6. How to Run the Project

To run this project, you need to have Python and the required libraries installed.
Clone the repository:

```Bash
git clone https://github.com/[your-username]/Handwritten-Digit-Recognition.git
Navigate to the project directory:
```

```Bash
cd Handwritten-Digit-Recognition
```

Run the Jupyter Notebook:
Open the ```Project 3.ipynb``` file in Jupyter Notebook and run the cells.
