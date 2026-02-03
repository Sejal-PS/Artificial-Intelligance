

# MNIST Digit Classification (TensorFlow) [ Artificial-Intelligance ]

This project uses **TensorFlow (Keras API)** to build and train a simple neural network for classifying handwritten digits from the **MNIST dataset**.

---

##  Overview

* Dataset: MNIST (28×28 grayscale images)
* Model: Fully Connected Neural Network
* Framework: TensorFlow 2.x
* Task: Digit classification (0–9)

---

##  Model

* Dense layer (128 units, ReLU)
* Output layer (10 units, Softmax)

---

##  Preprocessing

* Normalize pixel values to `[0, 1]`
* Flatten images into 784-length vectors

---

##  Training & Results

* Trained for **5 epochs**
* Test Accuracy: **~97.6%**

---

##  Requirements

```bash
pip install tensorflow
```

---

##  License

Open-source, for learning and educational use.


