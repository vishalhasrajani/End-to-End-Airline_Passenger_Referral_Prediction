# ✈️ Airline Referral Prediction Project

![Project Overview](https://github.com/vishalhasrajani/End-to-End-Airline_Passenger_Referral_Prediction/blob/main/Project-Airline-image.png)

---

## 📖 Introduction
This project aims to predict whether a passenger referred by an existing customer will book a flight, based on factors such as seat comfort, cabin service, travel class, food & beverage, entertainment service, and more. The model leverages machine learning classification techniques to make predictions based on historical passenger and booking data, assisting airlines in targeting marketing efforts effectively.

---

## 🎯 Objective
The primary objective is to predict whether passengers will refer the airline to friends. The dataset, scraped in Spring 2019, includes airline reviews from 2016 to 2019 for popular airlines worldwide, using both multiple-choice and free-text questions.

---

## 📊 Data Description
The dataset consists of 131,895 entries with the following columns:

1. **Airline**: Name of the airline.
2. **Overall**: Overall rating given by the passenger.
3. **Author**: Name of the reviewer.
4. **Review Date**: Date of the review.
5. **Customer Review**: Text of the customer review.
6. **Aircraft**: Type of aircraft.
7. **Traveller Type**: Type of traveler (solo, couple, family).
8. **Cabin**: Class of travel (economy, business, etc.).
9. **Route**: Route of the flight.
10. **Date Flown**: Date of the flight.
11. **Seat Comfort**: Rating for seat comfort.
12. **Cabin Service**: Rating for cabin service.
13. **Food & Beverage**: Rating for food and beverage service.
14. **Entertainment**: Rating for entertainment service.
15. **Ground Service**: Rating for ground service.
16. **Value for Money**: Rating for value for money.
17. **Recommended**: Whether the passenger recommended the airline or not.

---

## 🔍 Data Analysis and Preprocessing
- **Missing values**: Handled appropriately.
- **Data types**: Converted as necessary for model compatibility.
- **Feature Selection**: Based on relevance to the prediction task.
- **Exploratory Data Analysis (EDA)**: Conducted to understand feature distributions and relationships.

---

## 📈 Key Insights
1. **Traveler Type**: 37.22% travel solo, followed by couples and families.
2. **Travel Class**: 78.44% choose economy class.
3. **Cabin Service**: 50% gave a rating of 4.0 or 5.0, positively impacting airline business.
4. **Entertainment Service**: 30% are dissatisfied, rating it 1.0.
5. **Seat Comfort**: 38% rated 4.0 or 5.0, indicating poor seat comfort impacts satisfaction.
6. **Overall Rating**: 42% rated below 3.0, suggesting room for service improvements.

---

## 🛠️ Model Development
Several classification models were developed and evaluated:

1. **Logistic Regression**
2. **Decision Tree**
3. **Random Forest**
4. **K-Nearest Neighbor**
5. **Support Vector Machine**
6. **Naive Bayes**

---

## 🎯 Model Evaluation
- **Hyperparameter Tuning**: Used Grid Search CV for optimization.
- **Evaluation Metrics**: The Logistic Regression model performed best, with Support Vector Machine achieving the highest accuracy by a small margin.

---

## ⭐ Feature Importance
The most influential features for predicting whether a passenger will recommend an airline are:
1. **Overall Rating**
2. **Value for Money**

---

## 📈 Recommendations
To improve customer satisfaction and referrals, airlines should focus on:
1. **Cabin Service**
2. **Ground Service**
3. **Food & Beverage**
4. **Entertainment**
5. **Seat Comfort**

---

## 🏆 Conclusion
The project successfully developed a model with over 90% accuracy. By focusing on key service areas, airlines can boost customer satisfaction and referral rates, supporting business growth.

---

## 🔮 Future Work
- **Advanced Modeling**: Use ensemble methods for further refinement.
- **Additional Features**: Incorporate demographic data for personalized predictions.
- **Continuous Evaluation**: Update models with new data to maintain accuracy.

---

## 🚀 Deployment Demo

![Deployment Demo](https://github.com/vishalhasrajani/End-to-End-Airline_Passenger_Referral_Prediction/blob/main/Gradio_deployment-ezgif.com-video-to-gif-converter.gif)

The model has been deployed using Gradio for easy interaction and real-time predictions.
