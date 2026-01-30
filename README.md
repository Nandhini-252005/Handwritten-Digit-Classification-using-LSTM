# MNIST Digit Classification using LSTM (Long Short-Term Memory)

This project demonstrates handwritten digit classification on the MNIST dataset using a Long Short-Term Memory (LSTM) neural network built with TensorFlow and Keras.

Unlike traditional CNN-based approaches, this project treats image rows as sequential data, enabling the use of a Recurrent Neural Network for image classification.

---

## Dataset

**MNIST Dataset**
- 70,000 grayscale images
- Image size: 28×28 pixels
- Digits: 0 to 9
- 60,000 training images
- 10,000 testing images

---

## Model Architecture

The model used in this project is a **Long Short-Term Memory (LSTM) network**, a type of Recurrent Neural Network (RNN).

### Architecture Details:
- **Input Layer:** Sequence input (28 time steps × 28 features)
- **LSTM Layer:** 128 units
- **Output Layer:** Dense layer with 10 neurons (Softmax activation)

```text
Input(28×28 sequence) → LSTM(128) → Dense(10, Softmax)
