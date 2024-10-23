
# Fake Product Detection Using Naive Bayes and CNN

## Overview
Fake Product Detection is a system designed to identify counterfeit products by analyzing product logos. The project leverages both a **Naive Bayes Classifier** and a **Convolutional Neural Network (CNN)** to classify logos as either genuine or fake, helping consumers make informed purchasing decisions.

## Features
- Image preprocessing to convert and resize logo images.
- **Naive Bayes Classifier** for basic logo classification based on pixel values.
- **Convolutional Neural Network (CNN)** for deep learning-based logo classification.
- Integrated prediction system that combines outputs from both classifiers for improved accuracy.
- User-friendly interface for real-time logo authenticity testing.

## Technologies Used
- **Python**
- **OpenCV** - For image loading and preprocessing.
- **Numpy** - For array manipulation and numerical computations.
- **Scikit-learn** - For implementing the Naive Bayes classifier.
- **TensorFlow/Keras** - For building and training the CNN model.

## How It Works
1. The system takes an input logo image.
2. The image is preprocessed: converted to grayscale and resized to 64x64 pixels.
3. Features are extracted and passed to the Naive Bayes classifier for prediction.
4. The CNN processes the same preprocessed image for classification.
5. The final prediction combines results from both models to determine if the logo is genuine or fake.

## Setup Instructions

### 1. Clone the repository
```bash
git clone https://github.com/your-username/fake-product-detection.git
cd fake-product-detection
