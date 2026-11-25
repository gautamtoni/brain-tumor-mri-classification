# Brain Tumor MRI Classification Using Deep Learning

## Project Overview
This project uses a Convolutional Neural Network (CNN) to classify brain MRI images into four categories:

- Glioma
- Meningioma
- No Tumor
- Pituitary

This is an educational deep learning project and is not intended for medical diagnosis.

## Dataset
- Dataset: [Brain Tumor MRI Dataset – Kaggle](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset)
- Total images: 7,200
- Training images: 5,600
- Testing images: 1,600
- Validation images: 1,120 (20% of training data)

## Technologies Used
- Python
- TensorFlow / Keras
- CNN (Convolutional Neural Network)
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Data Preprocessing
- Image resizing to 224 × 224
- RGB image conversion
- Pixel normalization
- Data augmentation
- Training and validation split

## Model Architecture
The CNN model contains:
- Conv2D layers
- MaxPooling2D layers
- BatchNormalization
- GlobalAveragePooling2D
- Dense layers
- Dropout
- Softmax output layer

## Model Performance

**Test Accuracy: 82.69%**

| Class | Precision | Recall | F1-score |
|---|---:|---:|---:|
| Glioma | 0.91 | 0.69 | 0.78 |
| Meningioma | 0.80 | 0.62 | 0.70 |
| No Tumor | 0.78 | 1.00 | 0.88 |
| Pituitary | 0.84 | 0.99 | 0.91 |

## Features
- Multi-class brain MRI image classification
- CNN-based deep learning model
- Training and validation performance visualization
- Confusion matrix and classification report
- Single image prediction
- Reusable prediction function

## Project Structure
```text
brain-tumor-mri-classification/
│
├── notebooks/
│   └── brain_tumor_classification.ipynb
├── models/
│   └── brain_tumor_cnn_model.keras
├── results/
├── requirements.txt
└── README.md
```

## Limitations
This project is an educational prototype. Its performance is based on the selected dataset and does not establish clinical reliability. It must not be used to diagnose or make medical decisions.

## Future Improvements
- Transfer learning
- Model optimization
- Explainable AI using Grad-CAM
- Web application deployment
- External dataset validation

## Author
Developed as a Deep Learning portfolio project.
