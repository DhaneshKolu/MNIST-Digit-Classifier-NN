# MNIST Handwritten Digit Classification (Dense Neural Network)

## Project Overview
This project classifies handwritten digits (0–9) using a fully connected neural network (MLP).  
The MNIST dataset contains 70,000 grayscale images of handwritten digits.

## Key Concepts
- Multi-class Classification  
- Fully Connected Neural Network  
- Image Preprocessing & Normalization  
- Softmax Output Layer  
- Sparse Categorical Crossentropy  
- Training Curve Visualization  

## Technologies Used
- Python  
- TensorFlow / Keras  
- NumPy  
- Pandas  
- Matplotlib  

## Files in This Repository
- `MNIST(Dense NN).ipynb` — Model building, training, evaluation  
- `requirements.txt` — Dependencies  
- `/assets` — Optional folder for accuracy/loss plots  

## Model Architecture
- Flatten  
- Dense(128) → ReLU  
- Dense(64) → ReLU  
- Dense(10) → Softmax  

Loss: **Sparse Categorical Crossentropy**  
Optimizer: **Adam**

## Results
- Test Accuracy: **~X%**  
- Visualized training vs validation curves  
- Displayed sample predictions using softmax probabilities  

## How to Run
# MNIST-Digit-Classifier-NN
