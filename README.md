# Stock_Prediction

##  Stock Price Prediction using LSTM
This repository demonstrates stock price prediction using LSTM (Long Short-Term Memory) neural networks. We utilize historical stock price data for Apple Inc. (AAPL) obtained from Yahoo Finance and build an LSTM model to predict future stock prices. The model is trained on a portion of the data and tested on unseen data to evaluate its predictive performance.

## Getting Started
### Prerequisites
To run the code and experiments, you'll need the following:

  - Python (version 3.6 or later)    
  - Jupyter Notebook (to interact with the provided notebook)  
  - TensorFlow (for deep learning operations)   
  - Keras (for building and training the neural network) 
  - numpy (for array operations)   
  - matplotlib (for visualization)
  - pandas (Data manipulation and analysis)
  - yfinance (Fetch historical stock price data from Yahoo Finance)
<br>                   

You can install the required libraries using the following command:                               
 ```bash
pip install tensorflow keras yfinance pandas numpy matplotlib
```
 <br>
 
## Installation
To get started, follow these steps:   
  1. Clone the repository to your local machine:
```bash
git clone https://github.com/Guru02-GiT/Stock_Prediction.git
```
  2. Navigate to the project directory:
```bash
cd Stock_Prediction
```
  3. Run the Jupyter Notebook file:
```bash
jupyter notebook Stock_Price_Prediction_(LSTM).ipynb
```
<br>

## Procedure 
1. **Data Collection**: Historical AAPL stock prices fetched from Yahoo Finance for analysis.
2. **Data Preprocessing**: Closing prices scaled via Min-Max normalization. Data split into 80% training and 20% testing sets.
3. **Model Architecture**: LSTM network with two layers (50 units each), followed by two dense layers. MSE loss, Adam optimizer.
4. **Model Training**: Trained with batch size 1, 10 epochs, capturing temporal dependencies.
5. **Prediction**: Model predicts stock prices using last 60 days' data, then scaled back.
6. **Visualization**: Actual and predicted prices visualized for evaluation.
<br>

# Results
  - Upon running the Jupyter Notebook, you'll see the training progress, model predictions, and visualizations of the actual and predicted stock prices.
    
  - Feel free to experiment with different model architectures and hyperparameters to improve prediction accuracy.
