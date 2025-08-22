# MNIST 0 vs 1 Perceptron Classifier

A simple single-layer perceptron to classify handwritten digits 0 and 1 from the MNIST dataset.
This project demonstrates how a perceptron can learn a linearly separable problem and achieve near-perfect accuracy.

## 🔹 Features

Trains a perceptron on 0 vs 1 digits from MNIST.

Uses flattened grayscale images (28×28 pixels → 784 features).

Normalizes input pixels to [0, 1] for stable training.

Allows prediction on custom images.

## 🔹 Installation

Clone the repository:

`git clone https://github.com/Kiamehr5/0-1_Number_Identifier`
`cd mnist-perceptron`
**Install dependencies:**

`pip install numpy scikit-learn opencv-python matplotlib`

## 🔹 Usage
Run **Number_Identifier_Perceptron.ipynb** via **Google Colab** or **Jupyter Notebook**.

## 🔹 How It Works

Flatten the image → 28×28 pixels become a vector of 784 features.

Normalize pixel values to [0,1].

Perceptron training:

Initialize weights to zero.

For each sample, calculate prediction: y = step(w·x + b)

Update weights if misclassified.

Prediction: Same formula applied to new images.

## 🔹 Results

Accuracy on MNIST 0 vs 1 test set: ~0.9995 ✅

Very high because 0 and 1 digits are linearly separable.

## 🔹 License

This project is licensed under the MIT License.

### 🔹Any questions can be sent to kiamehr13922014@gmail.com
