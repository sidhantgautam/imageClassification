
# 🖼️ Image Classification on CIFAR-10 Dataset using CNN and Pre-trained Models

## 🚀 Project Overview
This project focuses on classifying images from the popular **CIFAR-10 dataset** using multiple convolutional neural network (CNN) architectures.  
We train, evaluate, and compare different models including a custom CNN, ResNet50, and MobileNetV2, demonstrating the power of transfer learning and deep learning techniques.

---

## ✅ Key Features

1. **Dataset Preparation**  
   - CIFAR-10 dataset (10 classes of small images)
   - Data normalization (values scaled to [0, 1])
   - One-hot encoding for categorical labels

2. **Data Visualization**  
   - Display sample images from training data with class labels
   - Visualize a grid of images and their respective labels

3. **Model Architectures**  
   - **Custom CNN**: Three convolutional layers followed by dense layers  
   - **ResNet50-based Model**: Transfer learning with ResNet50 as a feature extractor  
   - **MobileNetV2-based Model**: Transfer learning with MobileNetV2 as a feature extractor

4. **Training Strategy**  
   - Early stopping based on validation loss
   - Adam and SGD optimizers
   - Dropout layers to prevent overfitting
   - Batch normalization for better convergence

5. **Performance Metrics**  
   - Accuracy  
   - Precision  
   - Recall  
   - F1-score  
   All computed for each model and compared in a results table

6. **Visualization of Training Process**  
   - Plot training & validation accuracy and loss curves over epochs

7. **Predictions Visualization**  
   - Display sample test images with predicted labels

---

## 📊 Performance Comparison

| Model          | Accuracy | Precision | Recall | F1-Score |
|--------------|----------|-----------|--------|----------|
| Custom CNN   | ~76.53%  | ~77.72%   | ~76.53% | ~76.74% |
| ResNet50     | ~81.41%  | ~81.53%   | ~81.41% | ~81.35% |
| MobileNetV2  | ~77.75%  | ~78.57%   | ~77.75% | ~77.56% |

---

## ⚙️ How To Use

1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/cifar10-image-classification.git
   cd cifar10-image-classification
   ```

2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook `CIFAR10_Image_Classification.ipynb` in Google Colab or locally to train and evaluate models.

---

## 📚 Dependencies

- Python ≥ 3.7  
- TensorFlow ≥ 2.17  
- NumPy  
- scikit-learn  
- matplotlib  
- pandas

---

## 💡 Future Work

- Experiment with other architectures (e.g., DenseNet, VGG)
- Apply data augmentation techniques
- Hyperparameter tuning for performance boost
- Deploy model as a web service using Flask or FastAPI


