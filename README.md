# Titanic Exploratory Data Analysis (EDA)

## Project Overview

This project performs an Exploratory Data Analysis (EDA) on the Titanic dataset to identify the factors that influenced passenger survival. The analysis focuses on understanding how variables such as gender, passenger class, age, fare, and embarkation port relate to survival outcomes.

---

## Dataset

The dataset contains information about Titanic passengers, including:

* Passenger Class (`Pclass`)
* Name
* Sex
* Age
* Number of Siblings/Spouses Aboard (`SibSp`)
* Number of Parents/Children Aboard (`Parch`)
* Fare
* Cabin
* Embarkation Port (`Embarked`)
* Survival Status (`Survived`)

---

## Data Cleaning

The following preprocessing steps were performed:

* Missing values in the **Age** column were filled using the median age.
* Missing values in the **Embarked** column were filled using the mode (most frequent value).
* A new feature called **Has_Cabin** was created to indicate whether cabin information was available.
* The original **Cabin** column was removed due to a large number of missing values.

---

## Exploratory Analysis

The notebook includes:

1. Survival Distribution
2. Survival Rate by Gender
3. Survival Rate by Passenger Class
4. Age Distribution by Survival Status
5. Fare Distribution by Survival Status
6. Survival Rate by Embarkation Port

Visualizations were created using Matplotlib and Seaborn to identify patterns and relationships within the dataset.

---

## Key Findings

* Female passengers had significantly higher survival rates than male passengers.
* First-class passengers were more likely to survive than second- and third-class passengers.
* Survivors generally paid higher fares than non-survivors.
* Age showed a weaker relationship with survival compared to gender and passenger class.
* Passenger class, fare, and gender were the strongest factors associated with survival.

---

## Requirements

Install the required libraries using:

```bash
pip install -r requirements.txt
```

---

## Running the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
titanic_eda.ipynb
```

Run all cells from top to bottom to reproduce the analysis and visualizations.

---

## Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook
