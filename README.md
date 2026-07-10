# Landscape Image Classification
![Python](https://img.shields.io/badge/Python-3.12-blue?logo=python)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?logo=tensorflow)
![Keras](https://img.shields.io/badge/Keras-red?logo=keras)
![Google Colab](https://img.shields.io/badge/Google-Colab-yellow?logo=googlecolab)
![Deep Learning](https://img.shields.io/badge/Deep-Learning-success)

## Project Overview

This project investigates different Deep Learning strategies for landscape image classification using TensorFlow and Keras.

The study begins with a custom Convolutional Neural Network (CNN) and progressively incorporates more advanced techniques, including hyperparameter optimization with Keras Tuner, Transfer Learning based on MobileNetV2, Fine-Tuning and Data Augmentation.

The objective is not only to build an accurate image classifier, but also to compare how each technique affects the model performance and generalization capability.

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

> **Note:** The dataset is not included in this repository due to its size. Please download it from the official Kaggle page before running the notebook.

---

## Models Implemented

- **Model 1:** Basic CNN developed from scratch.
- **Model 2:** Improved CNN with a deeper architecture.
- **Model 3:** Hyperparameter optimization using Keras Tuner.
- **Model 4:** Transfer Learning with MobileNetV2.
- **Model 4 (Fine-Tuning):** Partial retraining of the pretrained network.
- **Model 5:** Data Augmentation applied to improve generalization.

---

## Best Results

| Model                 | Technique         | Validation Accuracy |
| --------------------- | ----------------- | ------------------: |
| Model 1               | Basic CNN         |               75.8% |
| Model 2               | Improved CNN      |               80.9% |
| Model 3               | Keras Tuner       |               83.2% |
| Model 4               | Transfer Learning |           **90.6%** |
| Model 4 (Fine-Tuning) | Fine-Tuning       |           **90.6%** |
| Model 5               | Data Augmentation |               88.4% |


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

## Trained Models

The trained model files (`.keras`) are not included in this repository due to GitHub file size limitations.

All experiments can be reproduced by running the notebook provided in the `notebook/` directory.

---

## Author

**Álvaro Sierras**

Master's Degree in Artificial Intelligence

GitHub: https://github.com/alvaroSV98

---

## Repository Structure

```text
Landscape-Image-Classification/
│
├── README.md
├── requirements.txt
├── notebook/
│   └── Landscape_Image_Classification.ipynb
├── results/
└── images/
```
