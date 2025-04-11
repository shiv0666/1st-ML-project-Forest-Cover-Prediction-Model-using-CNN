# 🌲 Forest Cover Prediction using Convolutional Neural Networks (CNN)

This project uses a **Convolutional Neural Network (CNN)** model to predict forest cover types from satellite images. It’s a beginner-level deep learning project designed to classify images into **binary categories** (e.g., presence or absence of wildfire effects). The model is trained on a custom dataset of forest images, organized into training, validation, and test folders.

## 🧠 Model Architecture

- Input Layer: 64x64 RGB images  
- Conv2D + ReLU Activation (32 filters)  
- MaxPooling Layer  
- Conv2D + ReLU Activation (64 filters)  
- MaxPooling Layer  
- Flatten Layer  
- Dense Layer (128 neurons, ReLU)  
- Dropout (50%)  
- Output Layer (Sigmoid for binary classification)


Each folder contains forest images labeled based on wildfire or vegetation cover type.

## 🚀 How to Run the Project

1. Clone the repository  
2. Ensure you have TensorFlow and required packages installed:
3. Place your dataset in the correct folder structure  
4. Run the Jupyter notebook: `Forest Cover Prediction Model using Computer Vision.ipynb`

## 📊 Training Details

- Image preprocessing using `ImageDataGenerator`  
- Binary classification using `binary_crossentropy` loss  
- Optimizer: **Adam**  
- Epochs: **10**  
- Trained with validation monitoring and accuracy tracking

## 📚 Key Learnings

- Building CNN models for image classification  
- Preprocessing images for training using Keras  
- Performing binary classification using sigmoid output  
- Evaluating and training deep learning models

## 🛠️ Tools & Libraries

- Python  
- TensorFlow / Keras  
- NumPy  
- PIL (Python Imaging Library)

