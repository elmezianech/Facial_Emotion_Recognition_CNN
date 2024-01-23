# Facial_Emotion_Recognition_CNN
This project focuses on advancing Facial Emotion Recognition (FER) by developing a robust model capable of accurately classifying emotions based on facial expressions. Leveraging sophisticated techniques, the model excels in understanding intricate facial features, ensuring precise emotional predictions. 


Dataset: https://www.kaggle.com/datasets/jonathanoheix/face-expression-recognition-dataset 



Key Techniques Employed: 


-Data Augmentation and Normalization: Enhanced the training dataset through data augmentation techniques. Applied normalization for consistent and standardized input data. 


-Complex CNN Model Architecture: Designed a powerful Convolutional Neural Network (CNN) model using TensorFlow and Keras. Captures intricate facial features through a hierarchical architecture: 1st to 4th CNN layers with varying filter sizes and pooling. Fully connected layers with dropout for preventing overfitting. 


-Callbacks for Efficient Training: Implemented early stopping, model checkpointing, and learning rate reduction callbacks: Early stopping prevents overfitting by monitoring validation loss. Model checkpoint saves the best model during training. Learning rate reduction adapts the learning rate during training. 


Model Evaluation: Evaluated model performance in different scenarios: 

Model 1: Created a baseline CNN model. 

Model 2: Incorporated data augmentation and added a dropout layer for improved generalization. 



Project Highlights: Uses advanced techniques such as data augmentation, normalization, and a complex CNN architecture. Combats overfitting with the incorporation of dropout layers. Efficient training with early stopping and learning rate reduction callbacks. Evaluation on different model scenarios provides insights into performance variations. 


-Prediction on Random Image: Demonstrated the model's capability by making predictions on a randomly selected facial image.
