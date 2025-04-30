# Plant Disease Detection Using CNN

## Project Overview
This project focuses on detecting plant leaf diseases using image classification with a Convolutional Neural Network (CNN).  
It uses the PlantVillage dataset, which contains 15 different classes of healthy and diseased leaves.  
The aim is to help automate early disease detection in crops using AI technologies.

---

## Dataset
- Source: [PlantVillage Dataset on Kaggle](https://www.kaggle.com/datasets/emmarex/plantdisease)
- Total Images: ~20,638 images
- Number of Classes: 15 (including healthy and various disease categories)

---

## Tools and Libraries Used
- Python
- TensorFlow / Keras
- Numpy
- Matplotlib
- Scikit-learn
- Google Colab

---

## Project Steps
- Downloaded dataset directly from Kaggle to Google Colab.
- Preprocessed the images (resized, normalized, split into training and validation sets).
- Built a CNN model with increasing complexity:
  - Conv2D(32 filters) ➔ Conv2D(64 filters) ➔ Conv2D(128 filters)
  - MaxPooling after each Conv layer
  - Flatten layer
  - Dense(128 units) with ReLU activation
  - Dropout for regularization (0.5 rate)
  - Dense(15 units) output layer with Softmax activation for multi-class classification.
- Model compiled with Adam optimizer and Categorical Crossentropy loss.
- Model trained for 10 epochs with validation monitoring.
- Evaluated model using:
  - Confusion Matrix
  - Classification Report (Precision, Recall, F1-Score)
  - Visualization of predictions on sample test images

---

## Model Performance
- Training Accuracy: **93.19%**
- Validation Accuracy: **91.91%**
- Final Loss: ~0.199 (Training) | ~0.290 (Validation)

---

## Confusion Matrix
(Include here your saved confusion matrix image if you want.)

---

## Future Improvements
- Apply data augmentation to further improve model robustness.
- Experiment with deeper architectures like ResNet or MobileNet.
- Deploy model as a web application for farmers and agritech solutions.

---

## Project Created By
**Bareera Mushthak**  
- Passionate about AI, Deep Learning, and Computer Vision.  
- Actively exploring AI engineering opportunities.  
- Always excited to solve real-world problems using technology!

---

## Connect With Me
- www.linkedin.com/in/bareera-mushthak

---

