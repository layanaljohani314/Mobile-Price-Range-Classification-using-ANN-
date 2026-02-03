# Mobile Price Range Classification using ANN 

This project implements an **Artificial Neural Network (ANN)** to classify mobile phone price ranges into four categories based on various technical specifications.

## Project Overview
This project focuses on building a predictive model using Deep Learning to classify mobile phones into four different price categories based on their hardware specifications.

The dataset contains various features such as battery power, RAM, internal memory, and camera resolution. By utilizing Artificial Neural Networks (ANN), the model learns the complex relationships between these technical specifications and the final market price category. The project involves data preprocessing, feature scaling, model architecture design, and performance evaluation using a Confusion Matrix.

## Model Architecture
#### 1.  Dataset Features

- Input Features: 20 features (RAM, Battery, Pixels, 3G/4G, etc.).

- Target Classes: 4 price ranges (0: Low, 1: Medium, 2: High, 3: Very High).

#### 2. Model Architecture
- Input Layer: 20 neurons (representing the features).

- Hidden Layer 1: 16 neurons with Sigmoid activation.

- Hidden Layer 2: 12 neurons with Sigmoid activation.

- Output Layer: 4 neurons with Softmax activation (for multi-class classification).

- Optimizer: Adam.

- Loss Function: Sparse Categorical Crossentropy.

#### 3. Final Performance
Training Accuracy: 99.07%

Testing Accuracy: 97.50%

Model Status: Healthy (No Overfitting detected).

##  Tech Stack
* **Python**: Core programming language.
* **TensorFlow / Keras**: For building and training the Deep Learning model.
* **Pandas & NumPy**: For data manipulation and numerical analysis.
* **Scikit-learn**: For data preprocessing, feature scaling, and evaluation metrics.
* **Matplotlib & Seaborn**: For data visualization and performance plotting.

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
