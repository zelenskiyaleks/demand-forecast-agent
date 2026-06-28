# demand-forecast-agent

End-to-end demand forecasting system with AI Agent, RAG, explainability and time series models.

---

## Project Goals

Build a production-like demand forecasting system that combines

- Time Series Forecasting
- RAG
- AI Agent
- Memory
- Guardrails

---

## Dataset

This project uses the M5 Forecasting dataset.

Download:

https://www.kaggle.com/competitions/m5-forecasting-accuracy/data

Place the files into

data/raw/m5/

---

## Project Structure

demand-forecast-agent/
│
├── README.md
├── configs
├── data
│   ├── external
│   ├── processed
│   └── raw
        └── m5/
                ├── calendar.csv
                ├── sales_train_validation.csv
                ├── sell_prices.csv
                ├── sample_submission.csv
                └── sales_train_evaluation.csv
├── docs
├── models
├── notebooks
├── reports
├── scripts
├── src
└── tests
