# Mobile Price Range Classification using ANN 

This project implements an **Artificial Neural Network (ANN)** to classify mobile phone price ranges into four categories based on various technical specifications.

## Project Overview
The goal of this project is to build a predictive model that estimates the price range of a mobile phone (0: Low Cost, 1: Medium Cost, 2: High Cost, 3: Very High Cost) by analyzing features such as RAM, Battery Power, Internal Memory, and more.

##  Tech Stack
* **Python**: Core programming language.
* **TensorFlow / Keras**: For building and training the Deep Learning model.
* **Pandas & NumPy**: For data manipulation and numerical analysis.
* **Scikit-learn**: For data preprocessing, feature scaling, and evaluation metrics.
* **Matplotlib & Seaborn**: For data visualization and performance plotting.

## Model Architecture
The Neural Network consists of:
1.  **Input Layer**: Accepts the technical features of the mobile devices.
2.  **Hidden Layers**: Multiple dense layers with **ReLU** activation functions to capture complex patterns.
3.  **Output Layer**: A dense layer with a **Softmax** activation function to output the probability for each of the 4 price categories.

## How to Run
1.  **Clone the repository**:
    ```bash
    git clone [https://github.com/layanaljohani314/Mobile-Price-Range-Classification-using-ANN-.git](https://github.com/layanaljohani314/Mobile-Price-Range-Classification-using-ANN-.git)
    ```

## Evaluation
The model's performance is evaluated using:
* **Accuracy & Loss Curves**: To monitor the learning process.
* **Confusion Matrix**: To analyze the classification accuracy for each price tier.
* **Classification Report**: Detailed Precision, Recall, and F1-score.

---
