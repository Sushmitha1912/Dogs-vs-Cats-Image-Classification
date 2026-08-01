# 🐶🐱 Dogs vs Cats Image Classification using CNN

## SkillCraft Technology - Machine Learning Internship (Task 3)

## 📌 Project Overview

This project implements a Convolutional Neural Network (CNN) using TensorFlow and Keras to classify images as either **Cat** or **Dog**. The model is trained on the Microsoft PetImages dataset and demonstrates the complete deep learning workflow, including data preprocessing, model building, training, evaluation, visualization, and model saving.

---

## 🎯 Objective

The objective of this project is to build a deep learning model capable of accurately classifying images of cats and dogs using a Convolutional Neural Network (CNN).

---

## 📂 Dataset

**Dataset:** Microsoft PetImages Dataset

The dataset contains two categories:

- 🐱 Cat
- 🐶 Dog

Images are automatically divided into training and validation datasets using TensorFlow.

Dataset Structure:

```
PetImages/
├── Cat/
└── Dog/
```

---

## 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Pillow
- Jupyter Notebook

---

## 🧠 Model Architecture

The CNN model consists of:

- Rescaling Layer
- Conv2D (32 Filters)
- MaxPooling2D
- Conv2D (64 Filters)
- MaxPooling2D
- Conv2D (128 Filters)
- MaxPooling2D
- Flatten Layer
- Dense Layer (128 Neurons)
- Output Layer (Sigmoid Activation)

---

## ⚙️ Training Configuration

| Parameter | Value |
|----------|-------|
| Image Size | 160 × 160 |
| Batch Size | 32 |
| Epochs | 5 |
| Optimizer | Adam |
| Loss Function | Binary Crossentropy |

---

## 📊 Results

| Metric | Value |
|--------|-------|
| Training Accuracy | **92.50%** |
| Validation Accuracy | **81.04%** |
| Epochs Completed | **5** |

The model successfully learned to classify cat and dog images with good accuracy. Training and validation accuracy graphs were generated to evaluate the model's performance.

---

## 📈 Output

- Successfully trained a CNN model for image classification.
- Generated training and validation accuracy graphs.
- Saved the trained model as **dogs_vs_cats.keras**.

---

## 📁 Project Structure

```
Dogs-vs-Cats/
│── dogs_vs_cats.ipynb
│── dogs_vs_cats.keras
│── README.md
│── requirements.txt
```

---

## ▶️ How to Run

1. Clone this repository.

2. Install the required libraries.

```bash
pip install -r requirements.txt
```

3. Download the Microsoft PetImages dataset.

4. Update the dataset path in the notebook.

5. Run all cells in the Jupyter Notebook.

6. The trained model will be saved as:

```
dogs_vs_cats.keras
```

---

## 📌 Conclusion

This project demonstrates how a Convolutional Neural Network (CNN) can effectively classify images of cats and dogs using TensorFlow and Keras. The model achieved **92.50% training accuracy** and **81.04% validation accuracy**, showing good performance on the validation dataset.

---

## 📄 License

This project was developed for educational purposes as part of the **SkillCraft Technology Machine Learning Internship – Task 3**.