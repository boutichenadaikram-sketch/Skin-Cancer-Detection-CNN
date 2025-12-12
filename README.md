# Skin Cancer Detection Using CNN

This project implements a Convolutional Neural Network (CNN) to detect skin cancer from images. It uses a dataset of skin lesion images and performs binary classification (malignant vs benign) with data preprocessing, augmentation, training, evaluation, and visualization.


## Libraries Used

- TensorFlow & Keras
- NumPy
- Matplotlib
- Seaborn
- scikit-learn
- Kaggle API


## Features / Implemented Steps

1. **Dataset Downloading**:  
   Downloaded the dataset from Kaggle using the Kaggle API and organized train/test directories.
   The project uses the [Melanoma Skin Cancer Dataset](https://www.kaggle.com/datasets/hasnainjaved/melanoma-skin-cancer-dataset-of-10000-images) from Kaggle.

3. **Data Preprocessing**:  
   - Images resized to 180x180 pixels  
   - Dataset split into training (80%) and validation (20%)  
   - Data caching, shuffling, and prefetching for performance

4. **Data Augmentation**:  
   - Random horizontal flip  
   - Random rotation  
   - Random zoom  

5. **CNN Model Architecture**:  
   - 3 Convolutional layers with ReLU activation and MaxPooling  
   - Flatten and Dense layers  
   - Dropout layer for regularization  
   - Output layer with Sigmoid activation (binary classification)

6. **Model Training**:  
   - Binary cross-entropy loss  
   - Adam optimizer  
   - Learning rate scheduler to reduce LR on plateau  
   - 20 epochs of training with training & validation accuracy/loss plots  

7. **Evaluation**:  
   - Confusion matrix on validation set  
   - Final evaluation on unseen test set  
   - Confusion matrix & detailed classification report for test set


##  Sample Visualizations

- Training & validation accuracy and loss plots
- Confusion matrix for validation and test sets



## 👩‍💻 Author

Boutiche Nada Ikram  
Master’s Student in Data, Algorithms & Machine Intelligence  
University of Palermo, Italy
