Name: Ritik Singh
Company: Acmegrade Pvt Ltd
Domain: Machine Learning
Duration: July 9, 2024 to September 9, 2024

## Overview of Stock price prediction project :
The Stock Price Prediction project aims to forecast stock prices using historical data through advanced machine learning techniques. This project leverages the power of Long Short-Term Memory (LSTM) neural networks to capture temporal dependencies in stock price movements, enabling accurate predictions for various stocks.

## Objective
The primary objective of this project is to provide an integrated platform that utilizes machine learning algorithms to predict future stock prices. By analyzing historical price data, the model helps investors make informed decisions based on expected future trends.

## Features
- **Data Analysis and Visualization:** 
  - Load and analyze historical stock prices from CSV files.
  - Visualize stock price trends for multiple companies using graphs.
  
- **Machine Learning Model:**
  - Implemented using LSTM networks to predict future stock prices.
  - Utilizes a Gated Recurrent Unit (GRU) layer to enhance model performance.
  
- **Performance Evaluation:**
  - The model is evaluated using metrics like R² score and Mean Squared Error (MSE).
  - Visual comparison of predicted vs. actual stock prices over time.

- **Data Security:**
  - Use of encryption techniques for secure handling of sensitive data (if applicable).

## Technologies Used
- **Programming Language:** Python
- **Libraries:** 
  - NumPy
  - Pandas
  - Matplotlib
  - Seaborn
  - Scikit-learn
  - Keras
  - TensorFlow

## Data Sources
- **Stock Prices Data:** Historical stock prices are stored in `prices.csv`.
- **Company Information:** Basic company data is obtained from `securities.csv`.

## Implementation Process
1. **Data Loading:**
   - Load the stock price data from CSV files using Pandas.

2. **Data Preprocessing:**
   - Analyze the dataset for missing values and duplicates.
   - Scale the stock prices to a range of 0 to 1 using MinMaxScaler.

3. **Data Splitting:**
   - Split the dataset into training and testing sets (80% training, 20% testing).
   - Prepare input features (X) and target variables (Y) for model training.

4. **Model Training:**
   - Define and compile the LSTM model using Keras.
   - Fit the model on the training data and validate it against the test data.

5. **Prediction and Evaluation:**
   - Make predictions on both training and testing datasets.
   - Evaluate model performance using R² score and visualize the predicted vs. actual prices.

6. **Results Storage:**
   - Store the prediction results in `results.csv` for further analysis.

## Usage
1. **Clone the Repository:**
   ```bash
   git clone <repository-url>
   cd <repository-directory>


-- Install Required Packages :
-pip install numpy pandas matplotlib seaborn scikit-learn keras tensorflow

-- Prepare Data:
-Ensure that prices.csv and securities.csv are present in the project directory.

--Run the Script:
-python <your_script_name>.py

--View Results:
The predicted stock prices and their comparison with actual prices will be displayed in the terminal and visualized in graphs.


output : ![image](https://github.com/user-attachments/assets/6ef36994-ae7e-4595-90d7-9c213336f19f)

