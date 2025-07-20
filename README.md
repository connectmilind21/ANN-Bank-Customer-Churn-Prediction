# ANN-Bank-Customer-Churn-Prediction
Bank Customer Churn Prediction In this project, a neural network model is built to predict customer churn for a banking service. The goal is to help the operations team identify customers more likely to churn and provide retention strategies.

# Bank Customer Churn Prediction
## Course: Introduction to Neural Networks

### Project Overview:
This project aims to analyze customer data from a banking institution to predict which customers are likely to churn. Using this prediction, the operations team can implement strategies to retain customers, thus reducing churn rates and improving customer satisfaction.

The project involves building a neural network model using TensorFlow and Keras to identify patterns in customer data that lead to churn. Additionally, recommendations on customer retention are provided based on the model's output.

### Skills & Tools Covered:
- **Exploratory Data Analysis (EDA)**: Understanding the data, visualizing distributions, and identifying patterns in the dataset.
- **Data Preprocessing**: Handling missing values, normalizing features, and encoding categorical variables.
- **TensorFlow & Keras**: Building and training a neural network model using deep learning frameworks.
- **Artificial Neural Networks (ANNs)**: Implementing a basic neural network to classify customers based on their likelihood to churn.
- **Regularization**: Applying techniques like dropout and L2 regularization to avoid overfitting and enhance model generalization.

### Project Details:
1. **Data Analysis**:
   - Load and clean the dataset.
   - Perform data exploration to uncover insights about the customer base.
   - Visualize the features and target variable (churn vs. non-churn).
   
2. **Data Preprocessing**:
   - Handle missing values.
   - Encode categorical features (e.g., gender, product usage) using one-hot encoding or label encoding.
   - Normalize numerical features to bring all inputs to a similar scale.
   
3. **Model Building**:
   - Define a neural network architecture with layers and activation functions.
   - Train the model using the training data.
   - Validate the model using cross-validation and evaluate it on a separate test set.

4. **Model Optimization**:
   - Implement regularization techniques like dropout or L2 regularization to improve model performance.
   - Fine-tune hyperparameters (e.g., learning rate, number of layers, number of units).

5. **Retention Recommendations**:
   - Based on the churn prediction, provide business-relevant recommendations to retain high-risk customers (e.g., personalized offers, customer support interventions).

### Installation:
To run the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/connectmilind21/bank-customer-churn-prediction.git
