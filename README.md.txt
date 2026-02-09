# 📊 Retail Demand Forecasting with Prophet

Time series forecasting project to predict retail product demand using Facebook Prophet.

## 🎯 Project Overview

Predictive model to forecast retail demand, helping optimize inventory management and reduce stockouts.

**Dataset:** [Retail Demand Forecasting Dataset](https://www.kaggle.com/datasets/rishavdash/retail-demand-forecasting-dataset)

## 🛠️ Tech Stack

- Python 3.8+
- Pandas, NumPy, Prophet, Scikit-learn
- Matplotlib, Seaborn
- Google Colab / Jupyter Notebook

## 📊 Methodology

1. Data acquisition via Kaggle API
2. Exploratory Data Analysis (EDA)
3. Automatic feature detection (date, target, regressors)
4. Prophet model with seasonality + external regressors
5. Evaluation with RMSE and MAPE
6. Forecast visualization and seasonal decomposition

## 📈 Key Results

- Strong weekly and yearly seasonality patterns identified
- Promotions significantly impact demand spikes
- Model successfully captures seasonal trends

## 🚀 How to Run

### Prerequisites
```bash
pip install -r requirements.txt
```

### Execution
1. Clone this repository
2. Download dataset from Kaggle
3. Run notebooks in order:
   - `01_exploratory_data_analysis.ipynb`
   - `02_demand_forecasting_model.ipynb`

## 📁 Project Structure
```
├── notebooks/          # Analysis and modeling notebooks
├── images/            # Visualizations
├── data/              # Dataset (not tracked in git)
└── requirements.txt   # Python dependencies
```

## 🔍 Future Improvements

- [ ] Compare with ARIMA and LSTM
- [ ] Hyperparameter tuning
- [ ] Deploy as REST API
- [ ] Create interactive dashboard

## 📝 License

MIT License

## 👤 Author

[Matheus Matielo] - [LinkedIn](https://www.linkedin.com/in/matheus-matielo-673321271/)