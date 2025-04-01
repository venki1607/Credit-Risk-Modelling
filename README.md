# Credit Risk Modelling

## Overview
Finance: Credit Risk Modelling is a **machine learning-based credit risk prediction tool** built using **Streamlit**. It helps financial institutions assess the probability of loan default, assign credit scores, and classify applicants into different risk categories.

## Features
- Interactive **Streamlit** web application for risk assessment.
- Calculates **default probability, credit score, and rating** based on user inputs.
- Uses **pretrained ML models** for accurate risk evaluation.
- Implements **feature scaling and preprocessing** for robust predictions.

## Technologies Used
- **Python**
- **Streamlit** for UI
- **Scikit-learn** for ML modeling
- **Pandas & NumPy** for data manipulation
- **Joblib** for model persistence

## Installation
### Prerequisites
Ensure you have Python 3.x and pip installed.

### Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/lauki-finance-risk-modelling.git
   cd lauki-finance-risk-modelling
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the Streamlit app:
   ```sh
   streamlit run main.py
   ```

## Usage
1. Enter the required details such as **age, income, loan amount, delinquency ratio, credit utilization, etc.**
2. Click on **Calculate Risk**.
3. The app will display **Default Probability, Credit Score, and Rating**.

## Project Structure
```
finance-risk-modelling/
│── main.py                # Streamlit UI for credit risk modelling
│── prediction_helper.py   # Functions for feature processing and prediction
│── artifacts/             # Pre-trained ML model and scaler
│── requirements.txt       # Dependencies
│── README.md              # Documentation
```

## Model Details
- **ML Model:** A trained regression-based model for credit risk analysis.
- **Scaler:** MinMaxScaler is used to normalize input features.
- **Feature Engineering:** Loan-to-income ratio, delinquency ratio, and categorical encodings.

## Contributing
Contributions are welcome! Follow these steps:
1. Fork the repository.
2. Create a new branch (`feature-branch`).
3. Commit your changes.
4. Push and submit a pull request.

## License
Venkatesh Surabathula 
codebasics.io

