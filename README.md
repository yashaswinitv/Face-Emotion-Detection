# Facial Emotion Recognition

![Facial Emotion Recognition](facial_recognition.png)

Recognizing human facial expressions plays a significant role in understanding emotions and behavior in various applications such as human-computer interaction, mental health analysis, and user experience evaluation.

This project focuses on detecting and classifying facial emotions in real-time using deep learning techniques. Human facial expressions are generally categorized into multiple emotional states such as **angry, happy, sad, neutral, and surprise**. Each of these emotions has distinct visual patterns that can be learned by a Convolutional Neural Network (CNN).

The system captures live video input through a webcam, detects faces using computer vision techniques, and predicts the corresponding emotion using a trained deep learning model.

---

## Usage

The application runs using a Python-based interface where the webcam captures real-time video. The detected face is processed and the predicted emotion is displayed on the screen.

To run the application:

```bash
python main.py
