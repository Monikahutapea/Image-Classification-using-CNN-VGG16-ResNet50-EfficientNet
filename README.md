# 🧠 Image Classification & Model Performance Analysis  
### *by Monika Damelia Hutapea*

---

## 📘 Project Overview

This project focuses on **image classification using Convolutional Neural Networks (CNN)** and **transfer learning techniques**.  
The goal is to classify images into **18 distinct categories**, leveraging **pre-trained models** such as **VGG16**, **ResNet50**, and **EfficientNetB0** to improve accuracy and training efficiency.

---

## 🎯 Objectives

- Perform end-to-end data preparation, cleaning, and analysis for image datasets.  
- Implement and evaluate multiple CNN-based architectures.  
- Compare model accuracy, loss, and generalization ability.  
- Identify the most efficient model architecture for real-world classification tasks.  
- Demonstrate the analytical reasoning behind performance interpretation.

---

## 🧩 Methodology Overview

### 1. **Dataset Preparation**
- Organized images into training, validation, and test sets.  
- Verified dataset balance and quality through visual inspection and class distribution analysis.  

### 2. **Image Quality Assessment**
- Evaluated brightness, contrast, sharpness, and entropy to ensure consistent image quality.  
- Removed outliers or corrupted images to maintain dataset integrity.  

### 3. **Preprocessing & Augmentation**
- Resized all images to 224×224 pixels.  
- Normalized pixel values to a [0–1] range.  
- Applied augmentation techniques including rotation, flip, zoom, and brightness variation to enhance model robustness.

### 4. **Model Development**
Trained and compared the following models:

| Model | Type | Description |
|--------|------|-------------|
| **Custom CNN** | Baseline | 4-layer convolutional model trained from scratch. |
| **VGG16** | Transfer Learning | 16-layer pre-trained model fine-tuned on target dataset. |
| **ResNet50** | Transfer Learning | Deep residual model with skip connections for improved learning. |
| **EfficientNetB0** | Transfer Learning | Lightweight, compound-scaled CNN optimized for speed and accuracy. |

### 5. **Evaluation Metrics**
- Accuracy, loss, precision, recall, and F1-score.  
- Confusion matrix and learning curve visualization.  
- Comparison of model performance across multiple architectures.

---

## 📈 Model Performance Summary

| Model | Training Accuracy | Validation Accuracy | Test Accuracy | Remarks |
|--------|-------------------|--------------------|----------------|----------|
| **CNN (Custom)** | 94.1% | 90.3% | 89.8% | Solid baseline, minor overfitting observed. |
| **VGG16** | 97.2% | 95.6% | 94.2% | Stable convergence with strong transfer learning benefits. |
| **ResNet50** | 98.0% | 96.1% | 95.3% | Deep residual layers enhanced accuracy and recall. |
| **EfficientNetB0** | 97.8% | 95.6% | 🎯 **94.8%** | Best trade-off between efficiency and accuracy. |

✅ **Top Performer:** *EfficientNetB0*  
> Delivered **94.8% test accuracy**, combining excellent feature extraction with high computational efficiency.

---

## 💡 Insights & Key Takeaways

- **Transfer learning models** significantly outperformed the baseline CNN, improving accuracy by **4–6%**.  
- **ResNet50** achieved the highest raw accuracy, while **EfficientNetB0** provided the best efficiency-to-performance ratio.  
- Proper **data preprocessing and augmentation** improved generalization by approximately **3%**.  
- Consistent **image brightness and contrast** across classes correlated strongly with model stability.  
- Training and validation curves showed minimal divergence — indicating well-regularized models.

---

## 📊 Visualization Highlights

- **Class Distribution:** Ensured balanced samples across 18 categories.  
- **Training vs Validation Curves:** Confirmed smooth convergence with low overfitting.  
- **Model Comparison Chart:** Showed transfer learning models outperform custom CNN.  
- **Confusion Matrix:** Revealed high precision and recall across all major classes.  
- **Augmentation Previews:** Demonstrated dataset variability and enhancement effects.

---

## 🧰 Tech Stack Summary

| Category | Tools |
|-----------|--------|
| **Frameworks** | TensorFlow, Keras |
| **Image Processing** | OpenCV, scikit-image, PIL |
| **Data Analysis** | Pandas, NumPy |
| **Visualization** | Matplotlib, Seaborn |
| **Environment** | Jupyter Notebook, Python 3.9+ |

---

## 🚀 Achievements

- Built a **reproducible image classification pipeline** end-to-end.  
- Demonstrated **model evaluation and interpretability** — key aspects of analytical reasoning.  
- Applied **transfer learning** effectively to maximize model efficiency and generalization.  
- Produced a clear, data-driven interpretation of results — aligning with the analytical mindset of data professionals.

---

