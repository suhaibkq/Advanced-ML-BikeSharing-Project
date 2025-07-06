# 🚲 Bike Sharing Case Study

![Bike Sharing](https://images.pexels.com/photos/6280594/pexels-photo-6280594.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2)

## 📌 Project Overview

This project is a case study from the **Artificial Intelligence and Machine Learning** program. It explores a real-world dataset from a bike-sharing system and demonstrates the use of **ensemble learning techniques** (Bagging, Boosting, Stacking) to analyze patterns in bike rental data and predict rental counts.

The project simulates the role of a data scientist at a company named **Travel Along**, tasked with providing data-driven insights and predictive models to optimize operations and enhance customer service.

---

## 🧠 Problem Statement

### Business Context

Bike-sharing systems automate the rental process and are widely adopted for their convenience and impact on traffic and the environment. Understanding customer behavior is key to managing demand.

### Objective

- Analyze factors influencing the number of bike rentals.
- Provide actionable insights for business improvement.
- Predict total bike rental counts using ensemble models.

---

## 📊 Dataset Description

The dataset includes rental data over two years with variables like weather conditions, time of day, and user type.

| Feature       | Description                                                                 |
|---------------|-----------------------------------------------------------------------------|
| `dteday`      | Date of rental                                                              |
| `season`      | Season (1: spring, 2: summer, 3: fall, 4: winter)                           |
| `yr`          | Year (0: 2011, 1: 2012)                                                     |
| `mnth`        | Month (1 to 12)                                                             |
| `hr`          | Hour (0 to 23)                                                              |
| `holiday`     | Whether the day is a holiday                                                |
| `weekday`     | Day of the week                                                             |
| `workingday`  | 1 if working day, 0 otherwise                                               |
| `weathersit`  | Weather condition (1–4 categories)                                          |
| `temp`        | Normalized temperature                                                      |
| `atemp`       | Normalized “feels like” temperature
