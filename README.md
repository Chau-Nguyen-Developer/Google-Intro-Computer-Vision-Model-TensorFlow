# Google-Intro-Computer-Vision-Model-TensorFlow
Practice creating a computer vision model that can recognize items of clothing with TensorFlow library. 
# Fashion MNIST Classifier

A TensorFlow/Keras model that classifies 28x28 grayscale images of clothing into 10 categories.

---

## Run in Google Colab

[![Open in Colab and make a copy for yourself](https://colab.research.google.com/drive/1hvBOlMK98F6j9mYdokjm8C55h07_3eGP?usp=sharing)

---

## Overview

This project trains a neural network on the Fashion MNIST dataset to recognize different types of clothing such as shirts, shoes, and bags. The model takes image data as input, preprocesses it, and predicts the most likely category.

---

## What the Notebook Does

* Loads the Fashion MNIST dataset
* Normalizes pixel values
* Flattens 28x28 images into 784-length vectors
* Builds a neural network using dense layers
* Trains the model
* Evaluates accuracy
* Uses callbacks to stop training early

---

## Results

* Training highest accuracy: ~90% (91.51%)
* Predicts clothing categories labeled from 0 to 9

0. T-shirt/top
1. Trouser
2. Pullover
3. Dress
4. Coat
5. Sandal
6. Shirt
7. Sneaker
8. Bag
9. Ankle boot

---

## Concepts Covered

* Neural networks (Dense layers)
* Data preprocessing and normalization
* Flattening image data (28x28 → 784)
* Model evaluation
* Callbacks (early stopping)

---

## How to Use

1. Click the "Open in Colab" link above. Make a copy for yourself.
2. Run all cells (Runtime → Run all)
3. View training progress and results
4. Please feel free to modify parameters or model structure if desired

---

## Project Structure

* `notebook.ipynb` — main Colab notebook containing all code

---

## Future Improvements

* Replace dense network with a Convolutional Neural Network (CNN)

---

## Notes

This project is intended as a learning exercise for me to understand the basics of deep learning, model training, and data preprocessing using TensorFlow and Keras.

