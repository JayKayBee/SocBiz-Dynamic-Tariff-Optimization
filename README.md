Dynamic Tariff Optimization for EV Charging Networks

An agentic AI system that forecasts EV charging demand and sets dynamic prices to increase revenue and utilization. It was built on 3M+ real-world records from Caltech (USA) and Shenzhen (China).

Society of Business, IIT Roorkee · May–June 2026

Results
+3.66% revenue over a flat ₹15/kWh tariff
34.9% higher utilization at dynamically priced stations compared with static ones (real Shenzhen data)
R² = 0.99 demand forecasting with lag features
How it works
Data: cleaned and unified the ACN (Caltech) and ST-EVCDP (Shenzhen) datasets into 5-minute slots per station.
Demand Prediction Agent: HistGradientBoosting with lag features forecasts station utilization.
Tariff Pricing Agent: applies surge or discount pricing using thresholds calibrated separately for each dataset.
Monitoring Agent: tracks revenue, pricing efficiency, congestion and customer response.


Datasets are not included. Download them from ACN-Data and ST-EVCDP, and place them in data/.

Tech

Python · Pandas · NumPy · scikit-learn · Matplotlib · Seaborn
