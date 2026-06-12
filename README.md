# Facial Emotion Detection Using Deep Learning

## Project Overview

This project focuses on multi-class facial emotion classification using deep learning techniques to identify four human emotions: **Happy, Sad, Neutral, and Surprise**. Multiple Artificial Neural Network (ANN), Convolutional Neural Network (CNN), and Transfer Learning models were developed and evaluated to determine the most effective approach for emotion recognition.

The project explores the impact of data augmentation, regularization techniques, hyperparameter tuning, and transfer learning on model performance. Development and experimentation were conducted in Google Colab using Python and leading machine learning libraries.

> Completed as part of the MIT Applied Data Science Program (ADSP), applying deep learning and computer vision techniques to solve a real-world image classification problem.

---

## Business Problem

Facial emotion recognition has applications across multiple domains, including:

- Human-computer interaction
- Customer experience analysis
- Mental health assessment
- E-learning platforms
- Smart surveillance systems

The objective was to develop a robust image classification model capable of accurately identifying emotional expressions from facial images.

---

## Technologies Used

- Python
- TensorFlow
- Keras
- Scikit-Learn
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Google Colab

---

## Skills Demonstrated

- Deep Learning
- Computer Vision
- Artificial Neural Networks (ANN)
- Convolutional Neural Networks (CNN)
- Transfer Learning
- Data Augmentation
- Hyperparameter Tuning
- Model Evaluation
- Performance Optimization
- Image Classification

---

## Methodology

### Data Preparation

- Image preprocessing and normalization
- Dataset splitting into training, validation, and testing sets
- Data augmentation to improve model generalization

### Model Development

Developed and evaluated multiple architectures:

- Artificial Neural Networks (ANN)
- Custom Convolutional Neural Networks (CNN)
- Transfer Learning using:
  - VGG16
  - ResNet V2
  - EfficientNet

### Model Optimization

Applied several techniques to improve model performance:

- Batch Normalization
- Dropout Regularization
- Learning Rate Optimization
- Adam Optimizer Tuning
- Hyperparameter Tuning

---

## Model Performance

The best-performing model was a custom CNN architecture consisting of:

- 4 Convolutional Layers
  - 64 filters
  - 32 filters
  - 128 filters
  - 256 filters
- ReLU activation functions
- MaxPooling layers
- Fully Connected Layer with 512 neurons
- Batch Normalization and Dropout regularization

### Results

| Metric | Performance |
|----------|----------:|
| Training Accuracy | 87% |
| Testing Accuracy | 78% |

### Key Findings

- Achieved over **90% accuracy** in identifying **Happy** and **Surprise** emotions.
- Most classification errors occurred between **Neutral** and **Sad** expressions due to their visual similarity.
- Data augmentation and regularization significantly reduced overfitting and improved model generalization.

---

## Sample Results

### Class Distribution

![Class Distribution](images/class_distribution.png)

### Training Accuracy

![Training Accuracy](images/training_accuracy.png)

### Training Loss

![Training Loss](images/training_loss.png)

### Confusion Matrix

![Confusion Matrix](images/confusion_matrix.png)

---

## Repository Structure

```text
facial-emotion-detection/
│
├── README.md
├── requirements.txt
├── Facial_Emotion_Detection.ipynb
|
├── images/
│   ├── class_distribution.png
│   ├── training_accuracy.png
│   ├── training_loss.png
│   └── confusion_matrix.png

```

---

## Key Takeaways

- Designed and evaluated multiple deep learning architectures for image classification.
- Improved model performance through transfer learning and regularization techniques.
- Demonstrated practical application of computer vision and deep learning concepts.
- Achieved strong emotion recognition performance while identifying opportunities for future improvements in distinguishing visually similar emotional states.

---

## Future Enhancements

- Expand the dataset to include additional emotional categories.
- Experiment with advanced architectures such as Vision Transformers (ViT).
- Deploy the model as a web application using Streamlit or Flask.
- Implement real-time emotion detection using live webcam input.

---

## Author

**Jayani Imalka**

Data Analytics | Business Intelligence | Applied Data Science

