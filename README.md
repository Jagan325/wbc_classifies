# wbc_classifies
## 📌 Overview

This project presents an **attention-based and explainable deep learning framework for automated White Blood Cell (WBC) classification** using medical blood-cell images.

The system combines **hybrid Convolutional Neural Network (CNN) architectures** with explainability techniques to improve both classification performance and model interpretability. The objective is to support **AI-assisted clinical decision support** by automatically identifying different types of white blood cells and providing visual explanations of the model's predictions.

## 🎯 Objectives

* Automate White Blood Cell image classification.
* Develop a deep learning-based medical image classification system.
* Improve feature representation using hybrid CNN architectures.
* Incorporate attention mechanisms for better feature selection.
* Provide interpretable predictions using **Grad-CAM**.
* Support clinical decision-support applications through explainable AI.

## 🧠 Methodology

The overall workflow consists of the following stages:

```text
WBC Image Dataset
        ↓
Image Preprocessing
        ↓
Data Augmentation
        ↓
Hybrid CNN Feature Extraction
        ↓
Attention-Based Feature Fusion
        ↓
Classification
        ↓
Grad-CAM Explainability
        ↓
Prediction / Clinical Decision Support
```

### Main Components

#### 1. Image Preprocessing

Medical blood-cell images are prepared for deep learning by applying suitable preprocessing and normalization techniques.

#### 2. Hybrid CNN Architecture

Multiple CNN-based feature extraction approaches are used to learn meaningful visual representations from WBC images.

#### 3. Attention Mechanism

An attention mechanism is incorporated to emphasize informative image features and improve feature representation.

#### 4. Classification

The extracted and fused features are passed to a classification network to identify the corresponding WBC type.

#### 5. Explainable AI

**Grad-CAM (Gradient-weighted Class Activation Mapping)** is used to visualize the image regions contributing to the model's prediction.

This helps improve model interpretability and allows users to understand which regions of the WBC image influenced the classification.

## 🧪 Technologies Used

* Python
* TensorFlow
* Keras
* Convolutional Neural Networks (CNN)
* OpenCV
* NumPy
* Pandas
* Grad-CAM
* Google Colab

## 🔬 Application

The project is designed for **medical image analysis and AI-assisted clinical decision support**, particularly for automated analysis of White Blood Cell images.

> **Note:** The system is intended as a research/decision-support tool and should not be considered a standalone medical diagnostic system.

## 📊 Evaluation

The model can be evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* ROC-AUC
* Inference Time
* Model Size

## 💡 Key Features

* Automated WBC classification
* Deep learning-based image analysis
* Attention-based feature learning
* Explainable AI using Grad-CAM
* Hybrid CNN architecture
* Medical image analysis
* Clinical decision-support orientation

## 📁 Suggested Repository Structure

```text
WBC-Attention-Explainable-DL/
│
├── dataset/
├── notebooks/
│   └── wbc_classification.ipynb
├── models/
├── results/
│   ├── confusion_matrix.png
│   └── gradcam_results/
├── src/
│   ├── preprocessing.py
│   ├── model.py
│   └── evaluation.py
├── requirements.txt
└── README.md
```

## 🚀 Future Enhancements

* Improve model generalization using larger and more diverse datasets.
* Explore additional attention mechanisms.
* Compare additional pretrained CNN architectures.
* Extend explainability using additional XAI methods.
* Develop a web-based interface for image prediction.
* Integrate the model into a clinical decision-support prototype.

## 👨‍💻 Author

**Jagan V**

Master of Technology – Information Technology
Sona College of Technology, Salem, India
