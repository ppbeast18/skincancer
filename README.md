<!-- PROJECT LOGO -->
<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/5/53/Skin_cancer_icon.png" alt="Logo" width="100" height="100">
</p>

<h1 align="center">🩺 Skin Cancer Detection using Deep Learning</h1>

<p align="center">
  A deep learning project to classify skin lesions and detect potential skin cancer using Convolutional Neural Networks (CNNs) and Transfer Learning.
  <br />
  <a href="https://github.com/ppbeast18/skincancer"><strong>Explore the docs »</strong></a>
  <br />
  <br />
  <a href="https://github.com/ppbeast18/skincancer/issues">Report Bug</a>
  ·
  <a href="https://github.com/ppbeast18/skincancer/issues">Request Feature</a>
</p>

---

## 📚 Table of Contents

- [About the Project](#-about-the-project)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [Dataset](#-dataset)
- [Model and Methodology](#-model-and-methodology)
- [Installation](#-installation)
- [Usage](#-usage)
- [Results and Evaluation](#-results-and-evaluation)
- [Future Improvements](#-future-improvements)
- [Contributing](#-contributing)
- [License](#-license)
- [Contact](#-contact)
- [Acknowledgments](#-acknowledgments)

---

## 💡 About the Project

Skin cancer is one of the most common cancers worldwide, but early detection can save lives.  
This project leverages **deep learning** to automatically classify **dermatological images** as benign or malignant.  

Using **Convolutional Neural Networks (CNNs)** and **transfer learning models** such as **ResNet**, **VGG16**, or **EfficientNet**, this repository demonstrates a complete workflow — from dataset preprocessing to model evaluation and visualization.

---

## ✨ Features

✅ Automated data preprocessing (resizing, normalization, augmentation)  
✅ Multiple model support (custom CNN & pretrained networks)  
✅ Model evaluation metrics (accuracy, F1-score, confusion matrix, ROC curve)  
✅ Visualization of training progress and predictions  
✅ Modular and extensible codebase  

---

## 🧠 Tech Stack

| Category | Tools / Libraries |
|-----------|-------------------|
| **Language** | Python 3.8+ |
| **Frameworks** | TensorFlow / Keras / PyTorch |
| **Data Handling** | NumPy, Pandas |
| **Visualization** | Matplotlib, Seaborn |
| **Image Processing** | OpenCV, PIL |
| **Development** | Jupyter Notebook, VSCode |

---


---

## 🧬 Dataset

This project supports public datasets such as:

- [HAM10000 Dataset](https://www.kaggle.com/kmader/skin-cancer-mnist-ham10000)
- [ISIC Archive](https://www.isic-archive.com/)

Each image is labeled as one of several skin lesion types, e.g.:

- **Melanoma (malignant)**
- **Benign Keratosis**
- **Nevus (benign mole)**
- **Basal Cell Carcinoma**, etc.

The dataset is split into training, validation, and testing sets (e.g., 70/20/10).

---

## ⚙️ Model and Methodology

1. **Data Preprocessing**
   - Resizing all images to a fixed shape (e.g., 224×224)
   - Normalization to `[0,1]`
   - Data augmentation (flip, rotate, zoom)

2. **Model Training**
   - Base CNN built from scratch or using transfer learning models such as:
     - ResNet50
     - VGG16
     - EfficientNetB0
   - Optimizer: Adam
   - Loss: Categorical Crossentropy

3. **Evaluation Metrics**
   - Accuracy
   - Precision / Recall / F1-Score
   - Confusion Matrix
   - ROC-AUC

---

## ⚡ Installation

Clone this repository:

```bash
git clone https://github.com/ppbeast18/skincancer.git
cd skincancer


