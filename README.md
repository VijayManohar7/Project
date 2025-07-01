# Alzheimer's Disease Detection - README
🧠 Project Overview

This project aims to build a deep learning-based pipeline using EfficientNetB7 to classify MRI brain images into four stages of Alzheimer's Disease:

MildDemented

ModerateDemented

NonDemented

VeryMildDemented

Additionally, we compare this deep learning model with traditional machine learning classifiers using features extracted from the CNN.

🔍 Dataset

The dataset used is the Alzheimer's Dataset (Kaggle) which contains MRI images of patients categorized into the 4 stages above.

✅ Workflow Summary

Data Exploration & Visualization: Class distribution shown using bar and pie charts.

Image Preprocessing: Resized images to 600x600, normalized inputs, and used ImageDataGenerator.

Modeling:

EfficientNetB7 pretrained on ImageNet

EarlyStopping to avoid overfitting

Logistic Regression, Random Forest, and SVM as baseline ML models using CNN-extracted features

Performance Evaluation:

Classification reports for all models

Prediction demo on a single test image

📈 Best Model

EfficientNetB7 (CNN) achieved a test accuracy of ~94.8%.

Among the traditional ML models:

Random Forest performed the best with ~88% accuracy, followed by SVM and Logistic Regression.

🏁 Conclusion

Deep learning with transfer learning (EfficientNetB7) significantly outperformed traditional machine learning models in this task. The model was able to generalize well with minimal tuning and provided high accuracy for Alzheimer's stage classification.

For production or real-time diagnostics, the EfficientNetB7 model would be the preferred choice.

