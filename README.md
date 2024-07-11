# BPN-Age-Prediction-Abalone
 Predicting the age of abalones using a Back Propagation Neural Network (BPN) implemented in PyTorch

1. Project Overview: This project implements a Back Propagation Neural Network (BPN) using PyTorch to predict the age of abalones from their physical characteristics. The model is trained and evaluated on the Abalone dataset using Google Colab.

2. Data Preprocessing: The dataset is loaded and preprocessed by performing one-hot encoding for categorical variables (gender) and standardizing continuous features. The data is split into training and testing sets using an 80:20 ratio.

3. Model Architecture: The neural network comprises an input layer with 10 nodes, two hidden layers with 64 and 32 nodes respectively (both using ReLU activation), and an output layer with 1 node for regression.

4. Loss Function and Optimizer: Mean Squared Error (MSE) is used as the loss function, and Stochastic Gradient Descent (SGD) with a learning rate of 0.1 is used as the optimizer.

5. Training and Evaluation: The model is trained for 100 epochs, and its performance is evaluated on the testing set by calculating the MSE loss. A dedicated evaluation function is implemented for this purpose.

6. Hyperparameter Tuning: Various hyperparameters such as learning rate, batch size, and the number of hidden nodes/layers are tuned. Observations are tabulated to understand their impact on the model's performance.

7. Additional Experiments: The impact of adding more layers is explored. Additionally, the Adagrad optimizer is tested and its performance compared with SGD, with observations noted.
