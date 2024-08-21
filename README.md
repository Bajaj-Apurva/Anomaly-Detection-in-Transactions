# Anomaly-Detection-in-Transactions
This project implements an anomaly detection system for transaction data using machine learning techniques. The aim is to identify unusual transactions that may indicate fraudulent activity or errors.

## Features
Data Visualization: Visualize various aspects of transaction data using Plotly.
Anomaly Detection: Detect anomalies in transaction amounts using statistical methods and the Isolation Forest algorithm.
User Input: Predict anomalies based on user-provided transaction data.

## Dataset
The dataset used in this project includes the following columns:

Transaction_ID: Unique identifier for each transaction.

Transaction_Amount: Amount of the transaction.

Transaction_Volume: Volume or frequency of transactions.

Average_Transaction_Amount: Average amount of transactions for the account.

Frequency_of_Transactions: Number of transactions over a specified period.

Time_Since_Last_Transaction: Time elapsed since the last transaction.

Day_of_Week: Day of the week the transaction occurred.

Time_of_Day: Time of day the transaction occurred.

Age: Age of the account holder.

Gender: Gender of the account holder.

Income: Income of the account holder.

Account_Type: Type of the account (e.g., savings, checking).

## Installation
To set up and run this project locally, follow these steps:
#### Prerequisites
Ensure you have Python 3.x installed. You'll also need the following Python packages:

pandas

numpy

plotly

Install these packages using pip:

pip install pandas numpy plotly scikit-learn

## Setup
#### Clone the repository

git clone https://github.com/Bajaj-Apurva/Anomaly-Detection-in-Transactions.git

cd anomaly-detection-in-transactions

## Usage
The project provides several functionalities:

Data Visualization: Generates visualizations for transaction amounts, distributions, and correlations.

Anomaly Detection: Identifies anomalies in transaction amounts using statistical methods and the Isolation Forest model.

User Interaction: Allows users to input transaction details and check for anomalies.

To interact with the project, run the main script and follow the prompts to input transaction details for anomaly detection.

## Future Scope
While the project provides a solid foundation for anomaly detection, there are several areas for future improvement:

#### Enhanced Features:
Incorporating additional features, such as transaction location or device information, could improve the model's accuracy and robustness.

#### Model Tuning: 
Further tuning of the Isolation Forest parameters or exploring other machine learning algorithms could optimize performance and detection capabilities.

#### Scalability:
Implementing the system in a production environment would require consideration of scalability and integration with real-time transaction systems.

## Conclusion
Overall, this project demonstrates the potential of combining statistical and machine learning techniques for effective anomaly detection in financial transactions. The methods and insights gained can be applied to various domains requiring the identification of unusual patterns and potential fraud.
