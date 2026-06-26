# Customer Churn Prediction with ANN

A machine learning project that predicts whether a bank customer is likely to churn using an Artificial Neural Network. The project covers preprocessing, model training, evaluation, and a Streamlit interface for interactive predictions.

## Why This Project Matters

Customer churn prediction helps businesses identify at-risk customers early and take retention action before revenue is lost. This project demonstrates an end-to-end supervised learning workflow for a practical business classification problem.

## Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn
- TensorFlow / Keras
- Streamlit

## Workflow

1. Load and inspect the customer dataset.
2. Encode categorical variables using label encoding and one-hot encoding.
3. Scale numerical features with `StandardScaler`.
4. Train an Artificial Neural Network with Keras.
5. Evaluate classification performance on test data.
6. Deploy an interactive Streamlit app for real-time churn prediction.

## Model Architecture

- Input layer based on customer features
- Dense hidden layers with ReLU activation
- Output layer with sigmoid activation for binary classification
- Optimizer: Adam
- Loss function: Binary Crossentropy

## Key Learning Outcomes

- Built a complete ANN classification pipeline.
- Practiced feature preprocessing for mixed categorical and numerical data.
- Connected a trained model to a simple user-facing prediction app.
- Applied a business-focused machine learning use case.

## How to Run

```bash
git clone https://github.com/marcelngoyi90/Churn_Prediction_ANN.git
cd Churn_Prediction_ANN
pip install -r requirements.txt
streamlit run app.py
```

If `requirements.txt` is not available, install the core packages manually:

```bash
pip install pandas numpy scikit-learn tensorflow streamlit
```

## Future Improvements

- Add precision, recall, F1-score, and ROC-AUC reporting.
- Save model artifacts in a dedicated `models/` directory.
- Add screenshots of the Streamlit interface.
- Package preprocessing and inference into reusable functions.
