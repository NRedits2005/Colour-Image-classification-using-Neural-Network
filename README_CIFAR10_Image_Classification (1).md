# CIFAR-10 Color Image Classification using Neural Networks

## 📌 Project Overview
This project demonstrates color image classification using a Neural Network trained on the CIFAR-10 dataset. CIFAR-10 is a widely used benchmark dataset consisting of 60,000 32x32 color images across 10 different classes. The model learns visual patterns from RGB images and predicts the correct class label.

## 🧠 Dataset Details (CIFAR-10)
- Total Images: 60,000  
- Training Images: 50,000  
- Test Images: 10,000  
- Image Size: 32 × 32 × 3 (RGB)  
- Classes:
  - Airplane
  - Automobile
  - Bird
  - Cat
  - Deer
  - Dog
  - Frog
  - Horse
  - Ship
  - Truck

## ⚙️ Model Architecture
The Neural Network is built using TensorFlow/Keras and includes:
- Input layer for 32x32 RGB images
- Flatten layer to convert image matrix into a vector
- Dense hidden layers with ReLU activation
- Output layer with Softmax activation for multi-class classification

## 🔄 Workflow
1. Load CIFAR-10 dataset
2. Normalize pixel values (0–255 → 0–1)
3. Build Neural Network model
4. Compile the model using Adam optimizer and categorical loss
5. Train the model on training data
6. Evaluate performance on test data
7. Predict image classes

## 📊 Performance Metrics
- Accuracy
- Loss
- Validation Accuracy

## 🧪 Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib

## ▶️ How to Run the Project
1. Install required libraries:
   ```bash
   pip install tensorflow numpy matplotlib
   ```
2. Run the training script:
   ```bash
   python train.py
   ```

## 🚀 Future Enhancements
- Replace Dense layers with CNN layers for higher accuracy
- Add data augmentation
- Implement transfer learning
- Deploy model using Streamlit or Flask

## 📚 References
- CIFAR-10 Dataset: https://www.cs.toronto.edu/~kriz/cifar.html
- TensorFlow Documentation: https://www.tensorflow.org/

---
Happy Learning! 🧠✨
