Pneumonia Detection using CNN & Transfer Learning

🚀 An advanced Deep Learning project that uses Convolutional Neural Networks (CNN) with ResNet50 Transfer Learning to classify Chest X-ray images into:

Normal

Pneumonia

📂 Dataset

Source: Kaggle Chest X-Ray Dataset

Two categories:

🫁 Pneumonia

💙 Normal

Preprocessed with:

Image resizing (224x224)

Normalization

Train/Validation/Test split

⚙️ Tech Stack

Python 🐍

TensorFlow / Keras 🤖

Google Colab (GPU) ⚡

NumPy, Matplotlib, Seaborn 📊

🧠 Model Architecture

Base Model: ResNet50 (pretrained on ImageNet)

Global Average Pooling + Dense layers

Dropout for regularization

Output: Binary classification (Normal vs Pneumonia)

📊 Results (After 5 Epochs)
              precision    recall  f1-score   support

      Normal       1.00      0.01      0.03       234
   Pneumonia       0.63      1.00      0.77       390

    accuracy                           0.63       624
   macro avg       0.81      0.51      0.40       624
weighted avg       0.77      0.63      0.49       624
