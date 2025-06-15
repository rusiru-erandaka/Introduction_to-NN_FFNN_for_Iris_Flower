# 🧑‍💻 Feedforward Neural Network for Iris Flower Classification 🌸

Welcome to the **Feedforward Neural Network (FFNN)** project for classifying Iris flower species! This project leverages deep learning concepts to accurately predict the species of an Iris flower based on its sepal and petal measurements. 🚀

---

## 🧠 **Theories and Concepts Used**

### 1. **Feedforward Neural Networks**
   - A type of Artificial Neural Network where connections between nodes do not form a cycle.
   - Each layer feeds its output to the next layer until the final output is generated.
   - Utilized for supervised learning tasks like classification and regression.

### 2. **Backpropagation**
   - An algorithm used to minimize the error in neural networks.
   - Works by propagating the error backwards through the network and adjusting weights using gradient descent.

### 3. **Activation Functions**
   - **ReLU (Rectified Linear Unit)**: Introduces non-linearity and handles vanishing gradients.
   - **Softmax**: Converts outputs into probabilities for multi-class classification probabilities.

### 4. **Loss Function**
   - **Categorical Cross-Entropy**: Measures the difference between the predicted probability distribution and the true distribution.

### 5. **Dataset: Iris Flower Dataset**
   - A famous dataset containing 150 samples of Iris flowers.
   - Features:
     - Sepal length and width
     - Petal length and width
   - Labels: Three classes - `Iris-setosa`, `Iris-versicolor`, `Iris-virginica`.

---

## ⚙️ **Project Workflow**

### 1. **Data Preprocessing** 🛠️
   - Load the Iris dataset using `sklearn`.
   - Normalize feature values for better training performance.
   - Split the data into training and test sets.

### 2. **Model Architecture** 🏗️
   - **Input Layer**: Accepts 4 features from the dataset.
   - **Hidden Layers**: Two fully connected layers with ReLU activation.
   - **Output Layer**: Three neurons with Softmax activation.

### 3. **Training the Model** 📊
   - Optimizer: **Adam** (Adaptive Moment Estimation).
   - Loss Function: **Categorical Cross-Entropy**.
   - Metrics: Accuracy.

### 4. **Evaluation and Results** 📈
   - Evaluate model performance on the test set.
   - Achieve high accuracy (>95%) with proper training and tuning.

---

## 🛠️ **How to Run This Project**

1. Clone this repository:
   ```bash
   git clone https://github.com/rusiru-erandaka/Introduction_to-NN_FFNN_for_Iris_Flower.git


## 🌟 Features
 - Simple and intuitive implementation of FFNN for beginners.

 - Uses the famous Iris flower dataset for classification.

 - Explains key neural network concepts with practical coding.

## 🤝 Contributing
 - Feel free to fork this repository and make contributions! Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change. Good Luck.


