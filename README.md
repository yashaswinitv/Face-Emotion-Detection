# Facial Emotion Recognition

Recognizing human facial expressions plays a significant role in understanding emotions and behavior in various applications such as human-computer interaction, mental health analysis, and user experience evaluation.

This project focuses on detecting and classifying facial emotions in real-time using deep learning techniques. Human facial expressions are generally categorized into multiple emotional states such as **angry, happy, sad, neutral, and surprise**. Each of these emotions has distinct visual patterns that can be learned by a **Convolutional Neural Network (CNN)**.

The system captures live video input through a webcam, detects faces using computer vision techniques, and predicts the corresponding emotion using a trained deep learning model.

---

## Usage

The application runs using a Python-based interface where the webcam captures real-time video. The detected face is processed and the predicted emotion is displayed on the screen.

---

## Dependencies

The project requires the following libraries:

* TensorFlow
* Keras
* OpenCV
* NumPy
* Flask

---

## Dataset

The model is trained on a facial expression dataset consisting of multiple labeled images categorized into different emotion classes. The dataset includes various human facial expressions captured under different lighting and conditions to improve model performance.

---

## Model Details

A Convolutional Neural Network (CNN) is used to train the model for emotion classification. The network learns spatial features from facial images and classifies them into predefined emotion categories.

The model is currently under training and will be updated with improved accuracy.

---

## Prediction

The system detects faces in real-time and predicts the emotion of the detected face. The prediction result is displayed continuously as the video stream is processed.

---

## Future Improvements

* Improve model accuracy with larger datasets
* Add more emotion categories
* Enhance UI for better user interaction
* Deploy the project on a web platform

---

## Authors

👤 **Yashaswini Talakadu Vijaykumar**

