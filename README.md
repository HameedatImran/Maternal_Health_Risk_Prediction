# Maternal_Health_Risk_Prediction
Models predicting maternal mortality
# Maternal Health Risk Prediction

A machine learning project predicting maternal health risk levels (low, mid, high) 
from routinely collectable vital signs — designed with low-resource clinical 
settings in mind.

## Clinical Context
Maternal mortality in Sub-Saharan Africa is driven partly by delayed recognition 
of high-risk pregnancies. This model explores whether basic vitals alone — blood 
pressure, blood glucose, temperature, heart rate — can reliably stratify risk 
at the point of care.

## Dataset
UCI Maternal Health Risk Dataset (n=1,014)  
Source: https://archive.ics.uci.edu/dataset/863/maternal+health+risk

## Results
| Metric | Value |
|---|---|
| Model | Random Forest (tuned) |
| Test Accuracy | 83% |
| Macro F1 | 0.83 |
| High-Risk Recall | 0.96 |

## Project Structure
- `data/` — raw dataset
- `models/` — saved model and scaler (.pkl)
- `outputs/` — all visualisations
- `maternal_health_risk.ipynb` — full analysis notebook

## Setup
```bash
pip install -r requirements.txt
```

## Tools
Python · pandas · scikit-learn · matplotlib · seaborn


