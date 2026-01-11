🤖 ANN Binary Classifier – Customer Churn Prediction

Predict whether a bank customer will churn (leave) or stay using an Artificial Neural Network (ANN).

📌 Features

- Data preprocessing & feature engineering (one-hot encoding, scaling)
- ANN with 2 hidden layers, ReLU activations, Dropout
- Binary classification with Sigmoid output
- Early stopping to prevent overfitting
- Model evaluation using accuracy & confusion matrix

📊 Dataset

- Churn_Modelling.csv – 10,000 customer records
- Features: Credit Score, Geography, Gender, Age, Tenure, Balance, NumOfProducts, HasCrCard, IsActiveMember, EstimatedSalary
  
🛠️ Libraries Used

- TensorFlow / Keras : ANN building & training
- Pandas : Data handling
- NumPy : Numerical computations
- Scikit-learn : Preprocessing, train/test split, metrics
- Matplotlib & Seaborn : Visualization
  
Target: Exited (1 = churn, 0 = stay)

📈 Key Insights

- ANN predicts churn with high accuracy ✅
- Dropout & early stopping reduce overfitting 🔒
- Key factors affecting churn: Credit Score, Balance, Tenure
