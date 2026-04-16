# Day-98-TensorFlow-basics

###  Overview

**TensorFlow** is an open-source **deep learning framework** developed by Google.
It is widely used to build and train **machine learning and neural network models**.

---

##  What is TensorFlow?

TensorFlow allows developers to:

* Build neural networks
* Train models efficiently
* Deploy ML models in real-world applications

It works using **tensors (multi-dimensional arrays)**.

---

##  Key Concepts

### 1️ Tensors

Basic data structure in TensorFlow.

```python id="t8k2p1"
import tensorflow as tf

tensor = tf.constant([1, 2, 3])
print(tensor)
```

---

### 2️ Model Building

TensorFlow provides high-level APIs like **Keras** to build models easily.

```python id="x9p3k2"
from tensorflow.keras.models import Sequential
from tensorflow.keras.layers import Dense

model = Sequential([
    Dense(10, activation='relu'),
    Dense(1)
])
```

---

### 3️ Model Compilation

Define loss function and optimizer.

```python id="z4m1k8"
model.compile(optimizer='adam', loss='mse')
```

---

### 4️ Model Training

```python id="c7d2l9"
model.fit(X_train, y_train, epochs=10)
```

---

### 5️ Prediction

```python id="p5q8n3"
predictions = model.predict(X_test)
```

---

##  Advantages

- Powerful deep learning framework
- Scalable and flexible
- Supports GPU/TPU acceleration

---

##  Disadvantages

* Can be complex for beginners
* Requires computational resources

---

##  Use Cases

* Image recognition
* Natural language processing
* Deep learning models
* AI applications

---

##  Key Takeaways

- TensorFlow is a powerful ML framework
- Uses tensors for computation
- Simplifies deep learning model building

---

