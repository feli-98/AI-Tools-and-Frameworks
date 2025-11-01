# 📘 AI Assignment – Practical & Ethical Applications
Machine Learning, Deep Learning, NLP, and Ethical AI Practices


## Overview

This repository contains my complete AI assignment submission, organized into four key tasks and a PDF document for the theoretic bit.

- **Task 1:** Iris Classification using Scikit-learn  
- **Task 2:** MNIST Digit Classification using TensorFlow  
- **Task 3:** Named Entity Recognition and Sentiment Analysis using spaCy  
- **Task 4:** Ethics & Troubleshooting in AI workflows


## 💻 Task 1: Iris Classification (Scikit-learn)

- Used `DecisionTreeClassifier` to classify iris species based on petal and sepal features.
- Evaluated model performance using accuracy, precision, recall, and classification report.
- Visualized the decision tree using `plot_tree()` for interpretability.
- Notebook includes clear comments and markdown structure for reproducibility.

📁 File: `Task1_Iris_Classification.ipynb`



## 💻 Task 2: MNIST Digit Classification (TensorFlow)

- Built a Convolutional Neural Network (CNN) using Keras to classify handwritten digits.
- Achieved over **95% test accuracy** on the MNIST dataset.
- Visualized predictions on 5 sample images with true vs predicted labels.
- Included fairness analysis by checking accuracy per digit class.

📁 File: `Task2_MNIST_CNN.ipynb`



## 💻 Task 3: NLP with spaCy

- Performed Named Entity Recognition (NER) on sample Amazon-style product reviews.
- Extracted product names and brand entities using spaCy’s pretrained model.
- Applied rule-based sentiment analysis using keyword matching.
- Output includes both entities and sentiment labels for each review.

📁 File: `Task3_spaCy_NLP.ipynb`



## 💻 Task 4: Ethics & Troubleshooting

## Ethical Considerations
- Identified potential biases in the MNIST model (e.g., digit style bias).
- Simulated fairness slicing by evaluating accuracy per digit class.
- Discussed mitigation strategies using TensorFlow Fairness Indicators and spaCy’s rule-based customization.

## Troubleshooting Challenge
- Debugged a faulty TensorFlow script:
  - Fixed input shape mismatch for Dense layers
  - Corrected loss function (`sparse_categorical_crossentropy`)
  - Reshaped data for compatibility with model architecture

📁 File: `Ethics_Troubleshooting.ipynb`

Each notebook demonstrates core AI techniques, model evaluation and ethical awareness.

