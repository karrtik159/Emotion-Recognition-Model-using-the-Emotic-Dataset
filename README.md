# Emotion Recognition Model using the Emotic Dataset
### Emotion Recognition Using ALEXNET Model with Adam Optimizer

![Anticipation Image in comparison with 26 Emotion Labels](image.png) <!-- Replace with an appropriate header image -->

This repository contains a Jupyter Notebook that demonstrates the process of training an emotion recognition model using the ALEXNET architecture and the Adam optimizer. The model is trained on the Emotic dataset, which is a collection of images annotated with rich emotion labels.

## Table of Contents
- [Introduction](#introduction)
- [Objective](#objective)
- [Dataset Preprocessing](#dataset-preprocessing)
- [Model Architecture](#model-architecture)
- [Training](#training)
- [Evaluation](#evaluation)
- [Co-Occurrence Matrix](#co-occurrence-matrix)
- [Image Prediction](#image-prediction)
- [Key Features of the Model](#key-features-of-the-model)
- [Future Notebooks](#future-notebooks)
- [Credits](#credits)
- [License](#license)



---

## Introduction  

This capstone project focuses on developing an **emotion recognition model** using deep learning techniques, specifically leveraging the **ALEXNET architecture** and the **Adam optimizer**. Emotion recognition plays a crucial role in applications such as **user experience analysis**, **mental health support**, **customer feedback systems**, and **human-computer interaction**. This project aims to contribute to this growing field by building a robust model that can recognize complex emotions from real-world images.  

## Objective  

The primary objective of this project is to build a deep learning-based model for classifying emotions and evaluate its performance on a real-world dataset. By fine-tuning the model and applying advanced evaluation techniques, we aim to deliver an efficient and scalable emotion recognition solution.

---

## Dataset Preprocessing  

We use the **Emotic dataset**, a well-known benchmark for emotion recognition tasks. The dataset consists of diverse images annotated with multiple emotion categories. The preprocessing pipeline involves:  

1. **Splitting the dataset** into training, validation, and test sets.  
2. **Data augmentation techniques** such as rotation, flipping, and normalization to improve model generalization.  
3. **Label encoding** to transform emotion categories into numerical representations suitable for deep learning models.

---

## Model Architecture  

The deep learning model is built using the **ALEXNET architecture**, known for its efficiency in image classification tasks. The architecture includes:  

- **Convolutional layers** to extract features from input images.  
- **Fully connected layers** for high-level abstraction and emotion classification.  
- **Dropout layers** to prevent overfitting.  

The architecture is implemented using **PyTorch** and optimized using the **Adam optimizer** with an appropriate learning rate and weight decay.

---

## Training  

The model is trained on the processed Emotic dataset using the following parameters:  

- **Optimizer:** Adam  
- **Loss Function:** Cross-Entropy Loss  
- **Epochs:** 10 (adjustable based on early stopping)  
- **Batch Size:** 56  

Detailed logs of the training process, including accuracy, loss, and learning curves, are available in the notebook.  

---

## Evaluation  

The model’s performance is evaluated using various metrics:  

1. **Confusion matrix** to visualize prediction accuracy across different emotion categories.  
2. **Precision, Recall, and F1-score** for a detailed understanding of class-wise performance.  
3. **Accuracy curves** and **loss curves** to analyze the model’s training behavior.  

---

## Co-Occurrence Matrix  

To further understand the model’s predictions, we generate a **co-occurrence matrix**, which helps analyze the relationships between predicted and true emotions. This provides insights into how well the model distinguishes between similar emotions, such as happiness and excitement.  

---

## Image Prediction  

We showcase the model’s capabilities by predicting emotions on sample images from the test set. The predictions are displayed alongside the confidence scores, highlighting the model's ability to classify emotions with a high degree of certainty.

---

## Key Features of the Model  

- **Trained on Emotic Dataset:** Our model is trained on a large, real-world dataset with diverse images and detailed emotion labels.  
- **Deep Learning-Based Emotion Recognition:** Built using state-of-the-art deep learning techniques for high accuracy and robustness.  
- **Fine-Tuned Performance:** The model is fine-tuned through multiple experiments to achieve competitive results in emotion classification.  
- **Capstone Project Outcome:** This project represents the culmination of our learning in deep learning, showcasing a real-world application of AI in emotion recognition.

---

## Explore the Notebook  

Feel free to explore the accompanying notebook for a detailed walkthrough of the entire process, including dataset preprocessing, model architecture, training, evaluation, and sample predictions.

---

## Future Work  

This project is a starting point, and future work could include:  

1. **Extending the model to multimodal emotion recognition** by incorporating text and audio modalities.  
2. **Deploying the model as a real-time emotion recognition API** for integration into web or mobile applications.  
3. **Experimenting with other deep learning architectures** such as ResNet or EfficientNet to further improve accuracy.  

---

## Credits  

- **ALEXNET Architecture:** [Original Paper](https://arxiv.org/ftp/arxiv/papers/1803/1803.01164.pdf)  
- **Emotic Dataset:** [Dataset Link](https://github.com/Tandon-A/emotic)  

---

## License  

MIT License  

Copyright (c) 2025 Kartik Baheti  

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:  

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.  

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES, OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

---

**Welcome to the Emotion Recognition Model Repository!** This project demonstrates the practical application of deep learning techniques to emotion recognition and serves as an example of a successful capstone project in AI/ML.  

---
