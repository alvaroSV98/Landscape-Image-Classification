# Landscape Image Classification

## Project Overview

This project explores different Deep Learning techniques for landscape image classification using TensorFlow and Keras.

The objective is to compare multiple approaches, starting from a basic Convolutional Neural Network (CNN) and progressively incorporating more advanced techniques such as hyperparameter optimization, Transfer Learning, Fine-Tuning and Data Augmentation.

The project has been developed as part of a Master's Degree in Artificial Intelligence.

---

## Dataset

The dataset contains images belonging to six different landscape categories:

-  Buildings
-  Forest
-  Glacier
-  Mountain
-  Sea
-  Street

Dataset source:

https://www.kaggle.com/datasets/puneet6060/intel-image-classification

---

## Models Implemented

- Model 1 – Basic CNN
- Model 2 – Improved CNN
- Model 3 – Hyperparameter Optimization (Keras Tuner)
- Model 4 – Transfer Learning (MobileNetV2)
- Model 4 – Fine-Tuning
- Model 5 – Data Augmentation

---

## Best Results

| Model | Validation Accuracy |
|-------|--------------------:|
| Basic CNN | 78.8% |
| Improved CNN | 80.9% |
| Keras Tuner | 83.2% |
| Transfer Learning | **90.6%** |
| Fine-Tuning | **90.6%** |
| Data Augmentation | 88.4% |

---

## Technologies

- Python
- TensorFlow
- Keras
- Keras Tuner
- NumPy
- Matplotlib
- Google Colab

---

## Future Improvements

- Test additional Transfer Learning architectures.
- Improve Data Augmentation strategies.
- Deploy the model as a web application.

---

## Author

Álvaro Sierras

Master's Degree in Artificial Intelligence
