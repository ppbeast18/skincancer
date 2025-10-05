
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


## 💡 About the Project

Skin cancer is one of the most common cancers worldwide, but early detection can save lives.  
This project leverages **deep learning** to automatically classify **dermatological images** as benign or malignant.  

Using **Convolutional Neural Networks (CNNs)** and **transfer learning models** such as **EfficientNet**, this repository demonstrates a complete workflow — from dataset preprocessing to model evaluation and visualization.

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
| **Frameworks** | TensorFlow / Keras |
| **Data Handling** | NumPy, Pandas |
| **Visualization** | Matplotlib, Seaborn |
| **Development** | Jupyter Notebook, VSCode,Goolge Colab |

---


---

## 🧬 Dataset


Each image is labeled as one of several skin lesion types, e.g.:

- **Melanoma (malignant)**
- **Benign Keratosis**

The dataset is split into training, validation, and testing sets.

---

## ⚙️ Model and Methodology

1. **Data Preprocessing**
   - Resizing all images to a fixed shape (e.g., 224×224)
   - Normalization to `[0,1]`
   - Data augmentation (flip, rotate, zoom)

2. **Model Training**
   - Base CNN built from scratch or using transfer learning models such as:
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


