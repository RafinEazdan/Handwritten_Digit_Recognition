# Handwritten_Digit_Recognition

# 🖋️ Handwritten Digit Recognition with CNN and Gradio

This project showcases a **Convolutional Neural Network (CNN)** model trained to recognize handwritten digits using the **MNIST dataset**. It features a user-friendly **Gradio** interface that allows users to draw digits and receive instant predictions.

## 📦 Dataset

- **Dataset:** MNIST  
- **Description:** A benchmark dataset consisting of 70,000 grayscale images (28×28 pixels) of handwritten digits (0–9).  
- **Usage:** The dataset was split into training and testing sets to train and evaluate the model's performance.

## 🧠 Model Overview

The CNN is designed with multiple convolutional, activation, pooling, and batch normalization layers, followed by dense layers and dropout for regularization. It was optimized using the Adam optimizer with a categorical crossentropy loss function and evaluated using accuracy metrics.

## 🔄 Data Augmentation

To enhance the model's ability to generalize and reduce overfitting, data augmentation techniques were applied. These included rotation, width/height shifts, shearing, and zooming.

## 🖼️ Gradio Interface

A simple and intuitive Gradio web interface enables real-time interaction with the model. Users can draw any digit (0–9) on a canvas, and the model will instantly predict the digit based on its training.

## ▶️ How to Run

1. **Install required libraries**: TensorFlow, Gradio, NumPy, and Matplotlib.
2. **Train the model** (or load a pre-trained one).
3. **Run the Gradio app** to interact with the digit recognizer through a browser.

## 📊 Results

- Achieved high training and validation accuracy on MNIST.
- Accurately recognizes digits drawn with varied handwriting styles.

## 🚀 Future Enhancements

- Add model confidence score visualization
- Deploy to cloud platforms or mobile devices
- Extend to recognize letters or symbols beyond digits

## 🤝 Acknowledgements

- TensorFlow/Keras for model building  
- Gradio for the interactive UI  
- MNIST for the dataset
