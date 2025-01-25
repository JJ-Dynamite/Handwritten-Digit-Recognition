# Handwritten Digit Recognition using Python and Deep Learning

A deep learning project that recognizes handwritten digits using Convolutional Neural Networks (CNN) and provides a graphical user interface for real-time digit recognition.

## Project Overview

This project implements a handwritten digit recognition system using the MNIST dataset. It uses a CNN model to achieve high accuracy in recognizing digits from 0-9. The application includes a GUI where users can draw digits and get instant predictions.

## Features

- Deep Learning model using CNN architecture
- Interactive GUI for drawing digits
- Real-time digit recognition
- High accuracy prediction
- Simple and user-friendly interface

## Prerequisites

- Python 3.x
- Required libraries:
  ```
  numpy
  tensorflow
  keras
  pillow
  ```

## Installation

1. Clone this repository or download the source code
2. Install the required dependencies:
   ```
   pip install numpy tensorflow keras pillow
   ```

## Project Structure

- `train_digit_recognizer.py`: Script to train the CNN model
- `gui_digit_recognizer.py`: GUI application for digit recognition
- `mnist.h5`: Trained model file (generated after training)

## Usage

1. First, train the model:

   ```
   python train_digit_recognizer.py
   ```

2. After training completes, run the GUI application:

   ```
   python gui_digit_recognizer.py
   ```

3. Draw a digit in the canvas area
4. Click "Recognise" to get the prediction
5. Use "Clear" to reset the canvas

## Model Architecture

The CNN model consists of:

- 2 Convolutional layers
- MaxPooling layer
- Dropout layers for regularization
- Dense layers for classification
- Softmax output layer for 10 classes (digits 0-9)

## Dataset

The project uses the MNIST dataset which includes:

- 60,000 training images
- 10,000 testing images
- 28x28 pixel grayscale images
- 10 classes (digits 0-9)

## Performance

- The model typically achieves ~99% accuracy on the test set
- Real-time predictions through the GUI interface
- Fast and efficient recognition


