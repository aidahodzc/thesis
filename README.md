HODZIC, Aida. _Forecasting Tourism Demand Using Artificial Neural Networks._ Diplomová práce, vedoucí Krištoufek, Ladislav.  
Praha, Univerzita Karlova, Fakulta sociálních věd, Institut ekonomických studií, 2025.

# Forecasting Tourism Demand Using Artificial Neural Networks

## Overview
This project explores the use of **artificial neural networks (ANNs)** for forecasting **monthly tourist arrivals** and **overnights** in **Croatia** from **2000–2024**, across **23 origin countries**.

## Modeling Framework
The model integrates:
- **Macroeconomic indicators**
- **Policy variables:** EU membership, Schengen, and euro adoption
- **Behavioral data:** Google Trends
- **Autoregressive lags**
- **Country-level embeddings** to capture market heterogeneity

## Key Findings
- In **stable periods**, demand is mainly driven by **seasonality** and **recent trends**, favoring **autoregressive benchmarks**.  
- During **disruptive periods** (e.g., **COVID-19**), **ANNs outperform** traditional models by capturing **nonlinear relationships** and **broader patterns**.  
- **Macroeconomic** and **behavioral signals** gain importance under **economic volatility**.  
- **High-volume markets** are often **underpredicted** post-crisis, though **targeted retraining** improves results.  
- **Non-Schengen countries** show **greater short-term sensitivity** due to **visa regimes** and **travel planning behaviors**.

## Conclusion
This thesis investigates **tourism demand forecasting** in **Croatia** using **monthly data** on **tourist arrivals** and **overnights** from **23 countries of origin**. The research analyzes a **comprehensive dataset** from the past **25 years**, comparing **neural network forecasts** with a **traditional autoregressive model**.  

Key findings include:
- **Models trained on full datasets** (including the **COVID-19** period) showed **better generalization** and **predictive accuracy** compared to models trained solely on **pre-pandemic data**. This demonstrates that exposure to **economic shocks** helps the model learn **robust forecasting patterns**.  
- **Overnights forecasts** showed **slightly higher accuracy** than **arrivals**, reflecting a more stable basis for demand prediction in **Croatia**.  
- **Benchmark AR models** performed well before the pandemic but struggled during the **COVID-19 recovery**, with significantly higher error metrics and lower explanatory power. In contrast, **ANNs consistently provided stronger predictive accuracy**.  
- **Per-country analysis** revealed that **ANNs** effectively captured **seasonality** and **trends** across most origin countries. However, they underpredicted **high-volume markets**, especially during major disruptions, likely due to the effect of **log transformation** and the model's **central tendency**.  
- **Factors influencing tourism demand** shift based on **external conditions**. Seasonality and **recent trends** were dominant in pre-pandemic periods, while **macroeconomic factors** (e.g., **exchange rates**, **consumer prices**) became more significant during the pandemic.

## Conclusion Summary
This thesis demonstrates that forecasting **tourism demand in Croatia** is most effective when combining **seasonal cycles**, **recent trends**, and **macroeconomic factors**. **ANNs** are well-equipped to capture both **predictable patterns** and **unexpected shifts**, providing valuable insights for **tourism authorities** and businesses in the **planning** and **strategy** phases. Despite some limitations (e.g., the use of **log transformation** and reliance on historical data), the findings emphasize the **flexibility** and **robustness** of **neural networks** in adapting to both **stable** and **volatile** tourism patterns.
