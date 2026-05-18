# CIFAR100-Object-Recognition
Object recognition project using the CIFAR-100 dataset with traditional machine learning and deep learning approaches, including HOG, PCA, SVM, and CNN models implemented in Python using Scikit-learn and TensorFlow.


This project explores image classification using both traditional machine learning and deep learning techniques on the CIFAR-100 dataset.

The implementation includes:

- HOG (Histogram of Oriented Gradients) feature extraction
- PCA (Principal Component Analysis)
- SVM (Support Vector Machine)
- Convolutional Neural Networks (CNN)

The project compares different classification approaches for both fine-grained and coarse-grained object recognition tasks.

---

## Models Implemented

### Traditional Machine Learning
- HOG feature extraction
- PCA dimensionality reduction
- SVM classifier

### Deep Learning
- Convolutional Neural Network (CNN) using TensorFlow/Keras

---

## Results

| Model | Classification Type | Accuracy |
|---|---|---|
| SVM | Fine Labels | 28.2% |
| SVM | Coarse Labels | 39.58% |
| CNN | Fine Labels | 36.69% |

The CNN achieved the best performance on fine-grained classification, while the SVM coarse classifier slightly exceeded the benchmark accuracy.

---

## Visualizations

The project includes:
- Sample image predictions
- HOG visualizations
- Confusion matrices
- Accuracy and loss graphs
- Classification reports

---

## Technologies Used

- Python
- NumPy
- Matplotlib
- Scikit-learn
- TensorFlow / Keras
- Google Colab

---

## Dataset

The project uses the CIFAR-100 dataset containing:
- 50,000 training images
- 10,000 testing images
- 100 fine categories
- 20 coarse categories

Image size: 32×32 RGB

---

## Project Structure

```text
CIFAR100-Object-Recognition/
│
├── CIFAR100_Object_Recognition.ipynb
├── README.md
└── results/
```

---

## Author

Ghada Al-Shahrani
