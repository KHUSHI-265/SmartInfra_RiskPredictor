# Smart Infrastructure Risk Predictor for Informal Settlements

Dev Delight Hack 2025 | Team Stack  
"Predict before the flood. Protect before the damage."

---

## Live Demo
https://hackathon-phi-fawn-18.vercel.app/

---

## Problem Statement
Every monsoon season, thousands of families in informal settlements are affected by flooding in the same locations year after year. Current systems are reactive and respond only after damage has occurred. There is no widely used machine learning-based early warning system for flood risk in such areas.

This is important because:
- A large portion of the population lives in informal settlements  
- Major cities experience repeated flooding  
- Authorities lack data-driven prioritization tools  
- Delayed response leads to loss of life and property  

---

## Solution
This project presents a machine learning model that predicts flood risk using three key inputs:
- Monsoon intensity  
- Urbanization level  
- Drainage efficiency  

Example:
- Mumbai: High rainfall, dense population, poor drainage → High risk (~89%)  
- Lohit: Low rainfall, sparse population, good drainage → Low risk  

---

## Dataset
- Total records: 23,040  
- Cities: Chennai, Delhi, Kolkata, Mumbai, Lohit, Nicobar  
- Target variable:  
  - 1 = Flood risk  
  - 0 = No risk  

Features used:
- monsoonintensity (0 to 1)  
- urbanization (0 to 1)  
- topographydrainage (0 to 1)  
- place (city name)  

---

## Model
A Random Forest Classifier is used for prediction.

Configuration:
- n_estimators = 400  
- max_depth = 12  

Performance:
- Accuracy: ~92%  
- Precision: ~91%  
- Recall: ~93%  
- F1 Score: ~92%  

---

## Features
- User-friendly web interface  
- Location-based input  
- Instant flood risk prediction  
- Visual feedback for risk levels  

---

## Tech Stack
- Python  
- pandas, numpy  
- scikit-learn  
- HTML, CSS, JavaScript  
- Git and GitHub  

---

## How to Run
1. Clone the repository:
[   git clone https://github.com/YOUR_USERNAME/SmartInfra_RiskPredictor.git  ](https://github.com/KHUSHI-265/SmartInfra_RiskPredictor.git)

2. Install dependencies:
   pip install -r requirements.txt  

3. Run the notebook or model file  

---

## Impact
- Helps authorities identify high-risk areas in advance  
- Supports NGOs in planning relief distribution  
- Gives residents time to prepare  
- Assists in improving urban infrastructure planning  

---

## Future Scope
- Integration with real-time weather or satellite data  
- Interactive mapping of risk zones  
- Automated alert systems  
- More advanced predictive models  

---

## Limitations
- Uses normalized input features  
- Requires manual input  
- Designed within hackathon scope  

---

## Team
Team Stack
