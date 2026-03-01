# Uber Fare Prediction App

This is a Machine Learning based Uber Fare Prediction Web App built using Streamlit.  
The app predicts the estimated fare based on trip details like distance, time, duration, passengers, and day (weekday/weekend).

---

# Project Overview

The model predicts the base fare using trained ML model and then dynamically applies:

-  Time-based multipliers (Peak / Night / Daytime)
-  Day-based multipliers (Weekday / Weekend Premium)
-  Distance and duration factor
-  Passenger count

The final fare is calculated after applying real-world surge logic.

---

# Technologies Used

- Python
- Streamlit
- Pandas
- NumPy
- Scikit-learn
- Joblib
