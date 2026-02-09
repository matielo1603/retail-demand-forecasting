📊 Retail Demand Forecasting with Prophet

End-to-end time series forecasting project focused on predicting retail product demand using Facebook Prophet, with emphasis on seasonality analysis and business impact.

🎯 Project Objective

Forecast future retail demand to support inventory planning, promotion strategy analysis, and stockout reduction, using historical sales data and temporal patterns.

The project explores how seasonality and promotional events influence demand behavior and evaluates Prophet’s suitability for retail forecasting scenarios.

Dataset:
Retail Demand Forecasting Dataset (Kaggle)
https://www.kaggle.com/datasets/rishavdash/retail-demand-forecasting-dataset

🧠 Business Context

Retail demand is highly seasonal and sensitive to promotions. Poor forecasts lead to:

Overstocking

Stockouts

Revenue loss

This project demonstrates how time series models can be applied to generate actionable demand forecasts aligned with real business decisions.

🛠️ Tech Stack

Python 3.8+

Data Processing: Pandas, NumPy

Modeling: Prophet, Scikit-learn

Visualization: Matplotlib, Seaborn

Environment: Jupyter Notebook / Google Colab

📊 Methodology

Dataset ingestion and preprocessing

Exploratory Data Analysis (trend, seasonality, anomalies)

Time series structuring for Prophet (ds, y)

Modeling with:

Weekly and yearly seasonality

Holiday / promotion effects

Model evaluation using:

RMSE

MAPE

Forecast visualization and interpretation of results

📈 Key Insights

Strong weekly and yearly seasonality patterns detected

Promotional periods generate clear demand spikes

Prophet effectively captures long-term trends and seasonal behavior

Model suitable for short- to medium-term retail demand forecasting

🚀 How to Run the Project

pip install -r requirements.txt

Execution Steps

Clone the repository

Download the dataset from Kaggle

Place the dataset inside the data/ directory

Run the notebook

📁 Project Structure

├── notebooks/           # EDA and modeling notebooks
├── images/              # Generated visualizations
├── data/                # Dataset (ignored by git)
├── requirements.txt     # Project dependencies
└── README.md

🔍 Future Improvements

 - Benchmark against ARIMA and SARIMA

 - Implement LSTM / deep learning models

 - Hyperparameter optimization

 - Deploy model as REST API

 - Build interactive dashboard (Streamlit / Power BI)

📝 License

MIT License

👤 Author

Matheus Matielo
Data & Analytics Enthusiast
https://www.linkedin.com/in/matheus-matielo-673321271/
