# **Plant Disease Detection using Convolutional Neural Networks (CNN)**

## **Introduction**

Plant diseases cause significant crop damage, resulting in economic losses for farmers and contributing to food insecurity. Traditional methods of disease identification are often labor-intensive, costly, and prone to human error. To address this, deep learning—particularly Convolutional Neural Networks (CNNs)—has emerged as a reliable and scalable approach for automated plant disease detection.  
Our system, trained on a dataset of 20,636 labeled leaf images across 3 plant species and 15 different diseases, achieves **91.7% accuracy on the validation set** and **89.5% accuracy on the test set**, demonstrating the effectiveness of CNNs in the field of precision agriculture.

---

## **Dataset Description**

- **Source**: [Kaggle - Plant Disease Dataset](https://www.kaggle.com/datasets/emmarex/plantdisease)
- **Total Images**: 20,636  
- **Number of Plant Species**: 3  
- **Number of Disease Classes**: 15  

### **Data Split**
- **Training Set**: 14,445 images (70%)  
- **Testing Set**: 6,191 images (30%)

---

## **Technologies Used**
- **Programming Language**: Python  
- **Libraries**:
  - TensorFlow / Keras  
  - NumPy  
  - OpenCV  
  - Matplotlib  
  - Streamlit (for the web interface)

---

## **Model Development Workflow**

1. **Image Preprocessing**
   - Resize, normalize, and augment images (flip, rotate, zoom)
2. **Model Architecture**
   - CNN built using Keras Sequential API
3. **Training**
   - 14,445 images used for training
4. **Evaluation**
   - Accuracy and loss metrics calculated on test set

---

## **Model Performance**

| Metric         | Value     |
|----------------|-----------|
| Training Accuracy  | 91.7%     |
| Testing Accuracy   | 89.5%     |
| Validation Loss    | 0.8265    |

---

## **Evaluation Metrics**
- **Accuracy**: 0.8953 (Test Set)
- **Loss**: 0.8265  
- **Final Model Accuracy**: 91.7%

---
## **Acknowledgments**
This project is inspired by the need for efficient agricultural tools to assist farmers and researchers in early disease detection. The dataset used was publicly available and curated from reliable sources.
