# 🧠 Breast Cancer Histopathological Image Classifier

A deep learning-based binary image classifier to detect breast cancer by distinguishing between benign and malignant histopathological images using Convolutional Neural Networks (CNN) and Transfer Learning.

---

## 🚀 Project Highlights

- Built a binary image classifier using **CNN architecture** and **MobileNetV2** via transfer learning.
- Developed a **custom dataset pipeline** including **image resizing**, **preprocessing**, and **data augmentation**.
- Applied **evaluation metrics** such as accuracy and loss curves to validate the model and avoid overfitting.
- Achieved high validation performance on unseen data.

---

## 🛠️ Tools & Technologies

- Python  
- TensorFlow / Keras  
- Convolutional Neural Networks (CNN)  
- Transfer Learning (MobileNetV2)  
- Data Augmentation  
- Matplotlib, Seaborn (for visualization)

---

## 📁 Project Structure

breast-cancer-classifier/
│
├── notebooks/
│ └── breast_cancer.ipynb
│
├── results/
│ ├── breast_cancer_cnn.pth
│
├── data/
│ └── README.md # Instructions to download data
│
├── requirements.txt
├── README.md


---

## 📊 Results

- ✅ **Model Accuracy**: 88%
- Model  is  available in the `results/` folder.

---

## 📦 Setup Instructions

```bash
git clone https://github.com/faizan-haider-AI/breast-cancer-classifier.git
cd breast-cancer-classifier
pip install -r requirements.txt
