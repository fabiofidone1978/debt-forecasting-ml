# Previsione Debito Pubblico (Random Forest)

Modello predittivo per la stima dell’andamento del debito pubblico italiano dal 2024 al 2030. Utilizza dati sintetici e tecniche di regressione con machine learning.

## Finalità

- Allenare un regressore su serie storiche sintetiche per simulare previsioni macroeconomiche.
- Offrire un esempio di modellazione basata su un solo attributo (l’anno) e validazione RMSE.

## Stack Tecnico

- Python 3
- Scikit-learn
- Pandas
- Matplotlib

## File

📦 debt-forecasting-ml
├── debt_forecasting.py
├── debt_historical_mock.csv
├── debt_forecast_2024_2030.csv
├── debt_forecast_rf.png
└── README.md

## Esecuzione

```bash
pip install pandas scikit-learn matplotlib
python debt_forecasting.py

Grafico previsionale del debito fino al 2030 e CSV strutturato per integrazione dashboard o modelli macro.****
