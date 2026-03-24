# Facial Emotion Recognition

Recognizing human facial expressions is important in many fields, such as human-computer interaction, psychology, and marketing. By analyzing facial expressions, we can predict the type of content that affects a person and gain insights into their emotional responses. Human facial expressions are typically classified into seven states: **angry, disgust, fear, happy, neutral, sad, and surprise**, each with unique features that are crucial for accurate classification.

## Usage
The code for this project is provided in a Jupyter Notebook and can be accessed [here](https://github.com/faizan387/Facial-Emotion-Recognition/blob/master/Facial_Expression_Training.ipynb).

## Dependencies
To run the project, you need the following Python libraries:
* Keras
* OpenCV
* Matplotlib
* Numpy
* TensorFlow
* Pandas
* Seaborn

## Dataset
The dataset consists of **35,887 samples**, divided into **80% for training** and **20% for testing**. These samples represent diverse human facial expressions, which are used to train the Convolutional Neural Network (CNN) model for classification.

## Sample Image
Below is an example image from the dataset showing a human facial expression:

<p align="center">
  <img width="500" alt="Facial Recognition Sample" src="image/facial_recognition.png">
</p>

## CNN Model Details
The CNN model used for facial expression recognition consists of multiple convolutional layers followed by pooling layers, which extract key features from images. These are followed by fully connected layers that classify the expression into one of the seven categories. The network is trained using labeled images from the dataset to minimize prediction error.

## Prediction Results
After training, the model can predict facial expressions in new images or video frames. Each second of a video can be analyzed, and the predicted expression is updated continuously. For example, a frame may be classified as **Neutral**, indicating that the person’s facial expression does not show a strong emotion at that moment.

---

## Authors
👤 **Yashaswini Talakadu Vijaykumar**  
* GitHub: yashaswinitv
