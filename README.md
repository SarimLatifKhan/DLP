# DLP
DLP Project

//Drive linkfor trained model and weights file:
https://drive.google.com/drive/folders/144BTaM_2yg7GS-bk1hCUyuvPjrM3aqH3



Facial Emotions Recognition for Deep Learning
Introduction
This project focuses on developing a deep learning model for facial emotions recognition. Emotion recognition is a vital task in various fields such as human-computer interaction, healthcare, and psychology. In this project, we aimed to accurately classify facial expressions into seven different emotion categories: sad, happy, fear, disgust, surprise, and two additional categories.

Dataset
The dataset used for training and evaluation was sourced from Kaggle. It comprises images of facial expressions annotated with corresponding emotion labels.

Model Architectures
We experimented with three different convolutional neural network (CNN) architectures:

VGG-19: A deep CNN architecture with 19 layers known for its simplicity and effectiveness.
ResNet: A deep residual network that addresses the degradation problem encountered in very deep networks.
Custom CNN: A CNN architecture designed specifically for this task, incorporating various layers, dropout for regularization, and max pooling layers.
Training Process
Each architecture was trained on the dataset using appropriate training techniques such as data augmentation, regularization, and optimization. The training process involved feeding the images through the network and updating the network's parameters based on the prediction error.

Results
After training the models on the dataset, we evaluated their performance based on accuracy. The custom CNN architecture outperformed the VGG-19 and ResNet architectures, achieving an accuracy in the range of 60-70%. The other two models yielded lower accuracies.

Model Analysis
To further analyze the models' performance, we conducted precision, accuracy, and confusion matrix analyses. These analyses provided insights into the models' strengths and weaknesses in classifying different facial expressions.

Conclusion
In conclusion, this project demonstrates the efficacy of deep learning models in facial emotions recognition. The custom CNN architecture, with its tailored design and training, emerged as the most effective for this specific task. Further improvements and fine-tuning could potentially enhance the accuracy and robustness of the model for real-world applications.