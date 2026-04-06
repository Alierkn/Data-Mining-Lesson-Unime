# Datasets README

This document provides an overview of the datasets used in the course, including their characteristics, data sources, and instructions for use.

## Titanic Dataset
- **Observations:** 891
- **Features:** 11
  - Passenger demographics (e.g., age, gender, class)
  - Survival status (0 = No, 1 = Yes)
  - Fare information

### Data Sources
- [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)

### Download Instructions
- Download the dataset from the above URL and unzip the files.

### Feature Descriptions
- **PassengerId:** Unique identifier for each passenger.
- **Survived:** Survival status (0 = No, 1 = Yes).
- **Pclass:** Ticket class (1st, 2nd, 3rd).
- **Name:** Name of the passenger.
- **Sex:** Gender of the passenger.
- **Age:** Age of the passenger.
- **SibSp:** Number of siblings/spouses aboard.
- **Parch:** Number of parents/children aboard.
- **Ticket:** Ticket number.
- **Fare:** Fare paid by the passenger.
- **Embarked:** Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

### Usage in Notebooks
- Refer to Notebook 1 for initial data exploration and cleaning.

---

## California Housing Dataset
- **Observations:** 20,640
- **Features:** 8
  - Median income
  - House age
  - Number of rooms
  - Location data

### Data Sources
- [California Housing Dataset](https://www.kaggle.com/c/california-housing-prices/data)

### Download Instructions
- Download the dataset from the provided URL.

### Feature Descriptions
- **MedInc:** Median income in block group.
- **HouseAge:** Median house age in block group.
- **AveRooms:** Average number of rooms per household.
- **AveOccup:** Average number of occupants per household.
- **Latitude:** Latitude of the block group.
- **Longitude:** Longitude of the block group.
- **MedHouseVal:** Median house value in block group.

### Usage in Notebooks
- Refer to Notebook 2 for application on regression analysis.