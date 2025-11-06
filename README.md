# Wind Turbine Power Prediction

This project predicts the **active power output** of a wind turbine using SCADA data.

## Models Compared
- Linear Regression  
- Random Forest  
- Neural Network (Keras)  
- Symbolic Regression (PySR)

| Model | MAE | RMSE | R² |
|-------|------|------|----|
| Linear Regression| 406.40 | 525.91 | 0.842 |
| Random Forest | 235.23 | 495.78 | 0.8598 |
| Neural Network | 202.17 | 356.32 | 0.9276 |
| Symbolic Regression | 319.15 | 443.11 | 0.8880 |

The neural network achieved the best predictive performance, while symbolic regression provided interpretable equations.

## Requirements
See `requirements.txt` for dependencies.
