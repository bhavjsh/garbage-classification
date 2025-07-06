# 🗑️ Garbage Classification using EfficientNetV2B2

This project was developed during my internship to classify waste images into 6 categories using image classification and transfer learning with EfficientNetV2B2.

The goal is to support smart waste management by automating waste type detection and encouraging eco-friendly disposal.



## 📂 Dataset

- [Kaggle Trash Type Image Dataset](https://www.kaggle.com/datasets/farzadnekouei/trash-type-image-dataset)
- Contains labeled images of:  
  **cardboard**, **glass**, **metal**, **paper**, **plastic**, **trash**



## ✅ Weekly Progress

### Week 1
- Set up Google Colab + Kaggle API
- Downloaded and explored dataset
- Created data generators
- Built base model using EfficientNetV2B2
- Trained for 2 epochs (basic run)

### Week 2
- Re-trained the model for 10 epochs
- Applied data augmentation (flip, rotate, zoom, shift)
- Plotted training vs validation accuracy and loss
- Organized results in separate notebook

### Week 3
- Fine-tuned the model (unfrozen base layers)
- Trained on GPU for better accuracy
- Tested with real trash images
- ✅ **Added unique prediction feature:**
  - Shows **eco-friendly tip** 🌱
  - Suggests **proper disposal** 🗑️

---

## 📁 Files Included

| File                            | Description                           |
|----------------------------------|---------------------------------------|
| `Week3_Garbage_Classifier.ipynb` | Final notebook with training + test   |
| `graph.png`                      | Accuracy/loss plot                    |
| `prediction_output.png`          | Model output with tip & disposal info |

---

## 📸 Sample Output
🧠 *Model predicted class*  
🌱 *Sustainability tip*  
🗑️ *Correct disposal advice*



## 🛠️ Tools & Frameworks
- Google Colab with T4 GPU
- TensorFlow / Keras
- EfficientNetV2B2 (transfer learning)



Built with 💻 + 💡 during IBM x Edunet Foundation Internship  
