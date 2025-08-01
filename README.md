
# Neural Network From Scratch (No Libraries)

This is a simple feedforward neural network (2-2-1) implemented **completely from scratch** using Python — no external libraries like NumPy, PyTorch, or TensorFlow.

## 🔍 Description

- **Inputs:** `x1 = 0.05`, `x2 = 0.10`  
- **Network Architecture:** 2 input neurons → 2 hidden neurons → 1 output neuron  
- **Activation Function:** Sigmoid  
- **Loss Function:** Mean Squared Error (MSE)  
- **Optimizer:** Manual Gradient Descent  
- **Target Output:** `0.01`  
- **Stopping Criteria:** Error drops below `1e-7`

## 🧠 Features

- Forward pass computation
- Manual gradient computation for backpropagation
- Learning via weight and bias updates
- Early stopping when error is sufficiently too low

## 📊 Sample Output

```
Epoch 0, Output: 0.751365, Error: 0.274812
...
Epoch 14000, Output: 0.010002, Error: 0.000000
Stopping early at epoch 14000, final error: 0.00000001
```

## 🧾 File Structure

```
📁 nn-from-scratch-no-libraries/
├── neural_net.py                ← Full implementation
├── README.md                    ← This file
├── nn_from_scratch_code.png     ← Code snapshot image
├── output_screenshot.png        ← (Optional) terminal training output
```

## 🤝 Credits

Created by [Dipak Balu Aghade](www.linkedin.com/in/dipak-aghade-0b2697326)  
as part of a deep learning self-study journey — starting from raw logic to PyTorch and beyond.
