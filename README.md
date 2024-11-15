# Advance_ML

## Advanced Machine Learning Personal Projects

This repository contains personal/academic projects completed as part of the Advanced Machine Learning course UCLA. The projects explore various advanced machine learning techniques, including Autoencoders, Convolutional Neural Networks (CNNs), Recurrent Neural Networks (RNNs), Generative Adversarial Networks (GANs), and ensemble learning.

Each project focuses on a unique challenge and employs state-of-the-art methodologies to address it, demonstrating practical applications of advanced machine learning models.

## Projects Overview

### 1. Autoencoder
Objective: Denoise a dataset using an encoder-decoder architecture.
Output: MSE: 0.003 (Class top performance)
Key Highlights:
Designed an autoencoder to remove noise from the data.
Utilized MLFlow for hyperparameter tuning with a random search strategy to optimize learning rates, layer configurations, and dropout rates.
Achieved significant noise reduction and clean data reconstruction.
Tools: Python, TensorFlow/Keras, MLFlow.

### 2. Convolutional Neural Network (CNN)
Objective: Classify images from the COCO dataset to detect the presence of people.
Output: accuracy: 92% (Class top 1% performance)
Key Highlights:
Leveraged transfer learning using the MobileNet architecture for computational efficiency.
Applied data augmentation techniques (rotation, flipping, zoom) and rescaling for better model generalization.
Optimized for accuracy and performance on large-scale datasets.
Tools: Python, TensorFlow/Keras.

### 3. Recurrent Neural Network (RNN)
Objective: Predict temperature based on historical weather patterns.
Output: accuracy: 91.19% (Class top performance)
Key Highlights:
Built a custom RNN from scratch, implementing forward and backward passes manually.
Conducted feature engineering, including extracting time-related features (e.g., hour of the day) and transformations for cyclic features.
Utilized time-series analysis techniques to handle sequential data.
Tools: Python, NumPy, TensorFlow/Keras.

### 4. Generative Adversarial Network (GAN)
Objective: Detect fake images using multi-modal data (image and text).
Output: accuracy: 97.59% (Class top 1% performance)
Key Highlights:
Built a multi-modal GAN that combines image and text features for classification.
Used ResNet as the backbone for image feature extraction and BERT for text embeddings.
Achieved a robust pipeline for detecting fake data in a noisy, real-world dataset.
Tools: Python, PyTorch, Hugging Face Transformers.

### 5. Ensemble Learning
Objective: Predict the number of vehicles and signals in an image using ensemble methods.
Key Highlights:
Trained base models, including:
MobileNet (pre-trained CNN),
Vanilla CNN (custom-built from scratch),
Mean model (baseline).
Explored ensemble techniques:
Simple average,
Linear regression,
XGBoost,
### Neural Networks (NN).
Evaluated and compared the performance of different ensemble methods for the task.
Tools: Python, TensorFlow/Keras, Scikit-learn, XGBoost.
Technologies and Tools
Programming Languages: Python.
Frameworks: TensorFlow, Keras, PyTorch, Hugging Face Transformers.
Libraries: NumPy, Scikit-learn, XGBoost, MLFlow.
Visualization: Matplotlib, Seaborn.
Version Control: Git.
