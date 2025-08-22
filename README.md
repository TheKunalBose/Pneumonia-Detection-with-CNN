# 🩺 Pneumonia Detection (Chest X-rays)

A Deep Learning project using **ResNet50 Transfer Learning** to classify chest X-rays into **Normal** or **Pneumonia**.  

---

## ⚙️ Tech Stack  
🐍 Python | 🤖 TensorFlow/Keras | 📊 NumPy, Matplotlib | ⚡ Google Colab  

---

## 📊 Results (5 Epochs)  

```
Accuracy: ~63%
Normal Recall: 0.01
Pneumonia Recall: 1.0
```

✅ Detects almost all Pneumonia cases  
❌ Misclassifies many Normal cases as Pneumonia  

---

## 🔍 Confusion Matrix  

- **Normal → Pneumonia** ❌  
- **Pneumonia → Pneumonia** ✅  

---

## 🚀 Next Steps  
- Add class weights (balance dataset)  
- Data augmentation 🖼️  
- Train for 10–15 epochs ⏳  
- EarlyStopping + LR scheduling  

---

## ▶️ Run  
1. Upload dataset to Google Drive:  
   ```
   /content/drive/MyDrive/ChestX-Ray/
   ```
2. Open notebook in Colab and train 📈  

---

✨ Built with ❤️ using CNNs + Transfer Learning  
