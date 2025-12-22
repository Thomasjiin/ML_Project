# Tesla Stock Trend Prediction

Machine learning pipeline for predicting **Tesla stock price trends** using historical market data.  
The task is formulated as a **trend classification problem** rather than exact price prediction.

---

Author: Yijia ZENG, Thomas JIN, Thibault GAUTHE

## Objective
- Predict future Tesla stock trends (**up / down**)
- Compare multiple models across different prediction horizons
- Focus on **multi-day trend prediction** (mainly 25-day horizon)

---

## Dataset
- Historical Tesla stock price data (daily)
- Features:
  - Open, High, Low, Close
  - Volume
- Target:
  - Future stock trend (1-day, 5-day, **25-day**)

---

## Pipeline
1. Data loading and preprocessing  
2. Feature engineering using technical indicators  
3. Model training with time-series–aware splitting  
4. Model evaluation and comparison  
5. Result visualization and interpretation  

---

## Feature Engineering
- Moving Averages  
- RSI  
- MACD  
- Volatility-related features  

All preprocessing respects **time-series constraints** (no data shuffling).

---

## Models

### Baseline
- Logistic Regression
- Linear SVM

### Tree-based
- Random Forest
- XGBoost

### Final Model
- **LightGBM**
- Time-series cross-validation
- 25-day future trend prediction

---

## Evaluation
- Time-series train/test split
- Classification accuracy
- Analysis using:
  - Model comparison
  - Predicted trend vs actual price
  - Probability calibration

---

## Results
- Best model: **LightGBM (25-day trend)**
- Accuracy: **~59%**
- Longer-horizon models show better stability than short-term models

---

## Challenges
- High noise in stock price movements
- Mild class imbalance
- Non-stationary market behavior
- Risk of overfitting in time-series data

---

## Future Work
- Improve bearish and neutral trend prediction
- Reduce bullish prediction bias
- Test generalization on other stocks
- Explore sequence-based models (e.g., LSTM)

---

## Project Structure
- Tesla_stock_trend_prediction.ipynb # Main notebook
- Tesla_stock_data.csv # Dataset
