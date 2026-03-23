Facial Emotion Recognition

Recognizing human facial expressions is important in various domains. By analyzing facial expressions, we can predict how content affects a person and gain insights into their emotional reactions. Human facial expressions can be categorized into seven states: angry, disgust, fear, happy, neutral, sad, and surprise. Each expression has unique features that are essential for accurate classification.

Usage

The code can be accessed through the provided Jupyter Notebook file
.

Dependencies
Keras
OpenCV
Matplotlib
NumPy
TensorFlow
Pandas
Seaborn
Dataset

The dataset consists of 35,887 samples, divided into 80% training and 20% testing data.

Sample Image from Dataset
<p align="center"> <img width="515" alt="Facial Expression Sample" src="./facial_recognition.png"> </p>
CNN Model Details

The Convolutional Neural Network (CNN) model used for this problem consists of multiple convolutional and pooling layers for feature extraction, followed by fully connected layers for classification. This architecture allows the model to learn unique patterns for each facial expression effectively.

Prediction Results

The model can classify facial expressions from video frames. For example, in a sample frame, the expression may be detected as Neutral, and predictions are updated every second.

Author

👤 Yashaswini Talakadu Vijaykumar
