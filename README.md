# Deep-Learning-based-Prescriptive-Maintenance-for-Machine-Health-Estimation
## Remaining Useful Life (RUL) Prediction using Machine Learning & Deep Learning
This project implements an end-to-end predictive maintenance system to estimate the Remaining Useful Life (RUL) of turbofan aircraft engines using Machine Learning and Deep Learning models.
The solution leverages time-series sensor data, feature engineering, and LSTM neural networks to model degradation patterns and predict engine failure cycles.
### Key Domains:
Predictive Maintenance | Time-Series Forecasting | Regression | Deep Learning | Industrial AI | Aerospace Analytics

### Dataset Description
- [x] **Dataset:** NASA C-MAPSS Turbofan Engine Dataset
- [x] **Data Type:** Multivariate time-series
- [x] **Features:**
  - Engine Unit ID,
  - Operational Cycles,
  - 3 Operational Settings,
  - 21 Sensor Measurements.

- [x] **Target Variable:** Remaining Useful Life (RUL)

- [x] **Industry Relevance:** Aerospace, Manufacturing, Heavy Machinery, Industrial IoT

### How does it work?

The data is first cleaned and scaled so the model can learn properly. A neural network with multiple layers is used to find patterns in the data. The model uses Huber Loss, which helps reduce the impact of extreme values. Early stopping is applied so the model stops training once it stops improving. This makes the model more stable, accurate, and reliable.
- **Loss Function**: Huber Loss  
- **Optimizer**: Adam  
- **Preprocessing**: Feature Extraction, Feature scaling



