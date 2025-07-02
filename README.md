## 🕺🏻 Fashion MNIST Classification

This repository contains a baseline implementation for classifying the **Fashion MNIST dataset** using TensorFlow and Keras.

---
### 📝 Project Overview

- **Dataset:** Fashion MNIST (60,000 training, 10,000 test images; 28x28 grayscale)
- **Task:** Multi-class classification (10 classes)
- **Model:** Sequencial Model; neural network (MLP) baseline

---
### ⚙️ Model Architecture

| Layer Type | Details |
|---|---|
| Input | Flatten (28x28 → 784) |
| Dense | 300 units, ReLU |
| Dense | 100 units, ReLU |
| Output | 10 units, Softmax |

- **Loss:** Sparse Categorical Crossentropy
- **Optimizer:** SGD
- **Metrics:** Accuracy
- **Epochs:** 30

---
### 🚀 Results

- **Validation Accuracy:** *87.70%*
- **Test Accuracy:** *87.62%*

---
### 🔧 Running Instructions

- [Run with Google Colab](https://colab.research.google.com/drive/1epxaNQHkUGV2i0aTZUupd8iYg6ygIBOS?usp=sharing) (recommended)

#### 📌 Requirements

* Python 3.8+
* TensorFlow 2, keras
* numpy, pandas, matplotlib


Install via [miniconda](https://www.anaconda.com/docs/getting-started/miniconda/main) (recommended, reffer to [TensorFlow](https://www.tensorflow.org/install)'s official website for more details and guidance):

```bash
conda install numpy pandas matplotlib
```
```bash
pip install tensorflow
```

---
### 📁 Files

| File | Description |
|---|---|
| `fashion_mnist_clf.ipynb` | Jupyter notebook|

---

### 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

### 🔗 References

- [Fashion MNIST Dataset](https://github.com/zalandoresearch/fashion-mnist)
- [TensorFlow Keras Documentation](https://www.tensorflow.org/api_docs/python/tf/keras)

---

