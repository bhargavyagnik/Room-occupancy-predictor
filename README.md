# Room-occupancy-predictor
Accurate occupancy detection of an office room from light, temperature, humidity and CO2 measurements using statistical learning models.


[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/bhargavyagnik/Room-occupancy-predictor/blob/main/AI_project_occupancy_prediction.ipynb)

Dataset can be accessed from [UCI repository](https://archive.ics.uci.edu/ml/datasets/Occupancy+Detection+)

### Occupancy detection of an office room from light, temperature, humidity and CO2 measurements using statistical learning models
---
**Attribute Information**
- date time year-month-day hour:minute:second
- Temperature, in Celsius
- Relative Humidity, %
- Light, in Lux
- CO2, in ppm
- Humidity Ratio, Derived quantity from temperature and relative humidity, in kgwater-vapor/kg-air
- Occupancy, 0 or 1, 0 for not occupied, 1 for occupied status

EDA, Processing , and classification algorithms like 
- Logistic Regression
- Decision tree
- SVM
- Random Forest
- KNN

and metrics like ROC, Precision Recall are calculated

Accuracies obtained using various classification algorithmns are :

| Method | Accuracy |
|--|--|
| Logistic Regression | 0.9822470817120622 |
| Decision Tree | 0.9897859922178989 |
| SVM | 0.9868677042801557 |
| Random Forest | 0.9922178988326849 |
| KNN | 0.9761673151750972 |



