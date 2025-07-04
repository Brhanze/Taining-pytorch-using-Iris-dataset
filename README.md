# 🌸 Iris Flower Classification using PyTorch

This project demonstrates how to build a simple neural network in **PyTorch** to classify the famous **Iris flower dataset** into three species: Setosa, Versicolor, and Virginica.

---

## 📊 Dataset

The [Iris dataset](https://en.wikipedia.org/wiki/Iris_flower_data_set) contains 150 samples with the following features:
- Sepal length (cm)
- Sepal width (cm)
- Petal length (cm)
- Petal width (cm)

And a label:
- 0 = Setosa
- 1 = Versicolor
- 2 = Virginica

---

## 🧠 Model Architecture

The model is a simple **feedforward neural network** built using PyTorch's `nn.Module`:
- Input Layer: 4 features
- Hidden Layer(s): Fully connected with ReLU activation
- Output Layer: 3 classes (softmax applied via `CrossEntropyLoss`)

---

## 🛠️ Technologies Used

- Python 🐍
- PyTorch 🔥
- NumPy
- Scikit-learn (for loading dataset and splitting)
- Matplotlib (for optional plotting)

---

## 🚀 How to Run

1. **Clone the repo**:
   ```bash
   git clone https://github.com/Brhanze/iris-pytorch.git
   cd iris-pytorch
