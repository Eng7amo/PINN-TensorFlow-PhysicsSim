# Physics-Informed Neural Network (PINN) Using TensorFlow

This project implements a Physics-Informed Neural Network (PINN) to approximate solutions for physical systems, likely governed by differential equations. It leverages TensorFlow and includes advanced training techniques like early stopping, dropout, batch normalization, and L2 regularization.

## 🧪 Key Features

- ✅ Deep learning architecture for solving physics-based problems
- ✅ Early stopping with custom callback
- ✅ Learning rate scheduler
- ✅ L2 Regularization
- ✅ Dropout & Batch Normalization
- ✅ 3D visualization using `matplotlib`

## 🧠 Architecture

- TensorFlow Keras-based custom model class (`PINN`)
- Dense layers with `LeakyReLU` activations
- Modular loss components for:
  - Residual loss
  - Boundary conditions
  - Initial conditions
