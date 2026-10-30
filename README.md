# Dog-Cat-image-classification
Project Description
This project uses a Convolutional Neural Network (CNN) to classify images into two categories: Cats and Dogs.

The model learns visual features such as edges, shapes, textures and patterns from images.
Objective
To develop an image classification system using deep learning and understand how CNNs process images.
Dataset
Cats vs Dogs dataset from TensorFlow Datasets.
- 80% Training Data
- 20% Testing Data
Technologies Used
- Python
- TensorFlow / Keras
- TensorFlow Datasets
- NumPy
- Matplotlib
Implementation Steps
1. Import the required libraries.
2. Load the Cats vs Dogs dataset.
3. Resize images to 128 × 128 pixels.
4. Normalize pixel values between 0 and 1.
5. Shuffle and batch the dataset.
6. Build a CNN model with three convolutional layers.
7. Add max-pooling layers to reduce feature dimensions.
8. Add Flatten, Dense and Dropout layers.
9. Compile the model using Adam optimizer and binary cross-entropy.
10. Train the CNN model.
11. Evaluate the model using testing images.
12. Visualize accuracy and loss graphs.
13. Predict whether a sample image is a cat or dog.
Model Architecture
Input Image (128 × 128 × 3)
          |
Conv2D – 32 Filters
          |
Max Pooling
          |
Conv2D – 64 Filters
          |
Max Pooling
          |
Conv2D – 128 Filters
          |
Max Pooling
          |
Flatten Layer
          |
Dense Layer (128)
          |
Dropout
          |
Output Layer (Sigmoid)
          |
      Cat or Dog


Expected Output
- Sample cat and dog images.
- Training and validation accuracy.
- Testing accuracy and loss.
- Predicted image classification.
Key Concepts
- Convolutional Neural Networks
- Image Preprocessing
- Feature Extraction
- Max Pooling
- Flatten Layer
- Dropout
- Binary Image Classification
