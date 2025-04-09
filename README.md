## Accounting + Stock Prediction with Neural Network [Acc_plus_SPRINN] - Stock Analysis Prediction Model

## 🎯 Project Overview

This project implements a stock price prediction model using two different machine learning approaches: linear regression and Long-Short-Term Memory (LSTM) neural networks. The goal is to provide predictive insights into stock price movements using historical data from Yahoo Finance.


## 💻 Features

- Automated stock data retrieval using `yfinance`
- Two prediction models:
  - Linear Regression
  - LSTM (Long Short-Term Memory) Neural Network
- Comprehensive data preprocessing
- Model training and evaluation
- Comparative analysis of prediction performance

## 📚 Prerequisites

- Python
- Tensorflow
- PyTorch
- yfinance
- pandas
- numpy
- Matlpotlib
- joblib
- sklearn

## 🚀 Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/Acc_plus_SPRINN.git
cd Acc_plus_SPRINN
```

2. Create a virtual environment (optional but recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

3. Install required packages:
```bash
pip install -r requirements.txt
```

## 📂 Project Structure

```
Accounting + Stock Prediction with Neural Network [Acc+SPRINN] - InnovateIN48 - 7th to 9th April 2025
Stock_Analysis_Prediction_Model/
│
├── data/                    # Raw and processed stock data
├── src/                     # Source code for data fetching and model training
├── models/                  # Saved trained models
├── tests/                   # Unit tests for various components
├── images/                # Model performance visualization
├── requirements.txt         # Project dependencies
└── main.py                  # Entry point for running the prediction model
```


## 🔧 Usage

### Fetching Stock Data

To fetch historical stock data:
```bash
python src/fetch_data.py
```

### Training Models & Running Predictions

To train both Linear Regression and LSTM models & run predictions and compare model performance:
```bash
python src/main.py
```

## ⚖️ Model Comparison

The project compares two machine learning models:

1. **Linear Regression**
   - Simple, interpretable model
   - Works well with linear relationships
   - Faster training time

2. **LSTM Neural Network**
   - Captures complex temporal dependencies
   - Better at handling sequential data
   - More complex architecture

## 📏 Performance Metrics

The performance of each model is evaluated using:
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)
- R-squared (R²) Score

Detailed performance metrics are visualized in the `pictures/` directory.

## 🧪 Testing

Run the test suite to verify model and data processing functionality:
```bash
python -m pytest tests/
```

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## ⚠️ Limitations

- Stock predictions are inherently probabilistic
- Model performance depends on market conditions
- Past performance does not guarantee future results

## 📝 License

Distributed under the FISGlobal License. See `LICENSE` for more information.

## 📫 Contact

<div align="center">

[![Github](https://img.shields.io/badge/-Github-000?style=flat&logo=Github&logoColor=white)](https://github.com/AbhijitChavan05)

**Abhijit Chavan 🧑‍💻**  


📧 abhijit.chavan@fisglobal.com

</div>

---
