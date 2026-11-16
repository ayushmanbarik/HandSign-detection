# HandSign-detection
Sign Language Recognition is a Deep Learning project that uses Convolutional Neural Networks (CNN) to recognize sign Language alphabet signs from images. The system performs image preprocessing, trains a CNN model, and predicts the corresponding sign. It aims to support accessible communication for the deaf and hard-of-hearing community.

## Objectives
- Recognize Indian Sign Language alphabet signs from images.
- Perform image preprocessing and normalization.
- Develop a CNN-based image classification model.
- Evaluate model performance using different metrics.
- Predict signs from new input images.

## Technologies Used
- Python
- Google Colab
- TensorFlow and Keras
- OpenCV
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Dataset
The dataset contains images organized into separate folders representing different Indian Sign Language alphabet signs.
- Total Images: 4,972 (as identified during initial dataset inspection)
- Number of Classes: 24
- Image Format: JPG, JPEG and PNG


## Project Workflow
1. Dataset loading and exploration.
2. Image preprocessing.
3. Image resizing to 64 × 64 pixels.
4. Pixel normalization.
5. Training, validation and testing split.
6. CNN model development.
7. Model training and validation.
8. Performance evaluation.
9. Confusion matrix and classification report.
10. Prediction using new images.
11. Saving the trained model.

## Model Architecture
The project uses a Convolutional Neural Network (CNN) consisting of:
- Convolutional layers
- Batch Normalization
- Max Pooling layers
- Flatten layer
- Dense layer
- Dropout layer
- Softmax output layer

## Model Evaluation
The model is evaluated using the following metrics:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

## Future Improvements
- Real-time sign recognition using a webcam.
- Recognition of continuous hand gestures.
- Sentence-level sign language translation.
- Development of a user-friendly web application.
- Expansion of the dataset to include more signs.

## Author
Ayushman Barik
