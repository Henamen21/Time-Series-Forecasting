# 📈 Tesla Stock Price Forecasting Using LSTM

This project develops a deep learning model using **Long Short-Term Memory (LSTM)** networks to forecast Tesla's stock prices for the next 6 months. It includes data collection, preprocessing, model building, evaluation, and interpretation of the results, with confidence intervals to assess prediction uncertainty.

---
<img width="1388" height="590" alt="image" src="https://github.com/user-attachments/assets/ebaef330-0ef1-4418-81d0-d90eae123857" />

---

## 📂 Project Structure

```
├── saved model/                  
├── notebooks/               
├── README.md              
```

---

## 🛠️ Techniques Used

* **LSTM Neural Network** for time series forecasting
* **MinMaxScaler** for feature scaling
* **Sequential modeling** with Keras
* **Confidence Interval Estimation** using residual standard deviation
* **Visualization** with Matplotlib

---

## 📉 Forecast Results

* **Forecast Horizon**: 6 months (approx. 180 trading days)
* **Trend**: The forecast follows a pattern consistent with recent historical data, suggesting stability or slight seasonality.
* **Volatility**: Confidence intervals widen as time progresses, indicating higher uncertainty in longer-term predictions.

---

## 📊 Evaluation

* **Root Mean Squared Error (RMSE)** and **Mean Absolute Error (MAE)** calculated on test data.
* Residuals analyzed for estimating forecast uncertainty.
* Visual inspection of forecast vs. actual data.

---

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/Henamen21/Time-Series-Forecasting.git
   cd Time-Series-Forecasting
   ```

2. Install requirements:

   ```bash
   pip install -r requirements.txt
   ```

---

## 📌 Key Insights

* The LSTM model effectively captures historical price trends.
* Forecast displays potential **seasonal-like waves**.
* Increasing confidence interval width implies **higher risk and lower reliability** in long-term forecasts.

---

## 📧 Contact

For questions or collaboration:
📬 **[henocktok@gmail.com](mailto:henocktok@gmail.com)**
