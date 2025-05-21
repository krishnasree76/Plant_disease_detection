# **Plant Disease Detection using Convolutional Neural Networks (CNN)**

## **Overview**
This project focuses on detecting and classifying plant diseases using deep learning techniques, specifically Convolutional Neural Networks (CNN). The objective is to help automate the process of identifying diseased plant leaves, enabling early intervention and improved crop management.

## **Key Features**
- Automatic classification of multiple plant diseases from leaf images.
- High accuracy deep learning model built using CNN.
- Real-time prediction through a user-friendly Streamlit interface.
- Image pre-processing and augmentation for robust training.
- Easily extendable to support more plant species and disease types.

## **Technologies Used**
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- OpenCV
- Streamlit

## **Dataset**
- The dataset consists of segmented leaf images categorized into healthy and diseased classes.
- Each class is organized into separate folders for training and testing.
- The dataset supports various crops, including tomato, potato, apple, corn, and grape.


## **Model Workflow**
1. Load and preprocess the image dataset.
2. Apply data augmentation techniques to reduce overfitting.
3. Build and train the CNN model.
4. Evaluate model performance using validation data.
5. Use the trained model for real-time predictions on new leaf images.

## **Model Performance**
- **Training Accuracy**: 91.78%
- **Validation Loss**: 0.8265
- The model demonstrates strong performance in classifying diseased and healthy plant leaves with high reliability.

## **Future Improvements**
- Integrate with mobile or drone-based systems for real-time field detection.
- Expand dataset with more plant species and disease types.
- Enhance model accuracy using transfer learning.
- Enable multi-label classification for detecting co-infections.

## **Acknowledgments**
This project is inspired by the need for efficient agricultural tools to assist farmers and researchers in early disease detection. The dataset used was publicly available and curated from reliable sources.
