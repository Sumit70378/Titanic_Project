# 🚢 Titanic Survival Prediction

A machine learning project analyzing passenger data from the RMS Titanic to explore key survival factors and predict passenger survival using classification algorithms.

---

## 📌 Overview

The sinking of the Titanic is one of the most infamous shipwrecks in history. While there was some element of luck involved in surviving, evidence shows certain groups—such as women, children, and upper-class passengers—were more likely to survive than others.

This project implements an end-to-end data science workflow:
1. **Exploratory Data Analysis (EDA):** Visualizing demographics, passenger class, ticket fare, and family sizes to identify trends.
2. **Feature Engineering & Preprocessing:** Handling missing values, encoding categorical variables, and scaling features.
3. **Model Building & Evaluation:** Training classification models to accurately predict survival outcomes.

---

## 📊 Dataset Description

The dataset typically includes the following features:

| Feature | Description | Key Values / Notes |
| :--- | :--- | :--- |
| `PassengerId` | Unique identifier for each passenger | Integer |
| `Survived` | Target variable: survival status | `0` = No, `1` = Yes |
| `Pclass` | Ticket class | `1` = 1st, `2` = 2nd, `3` = 3rd |
| `Name` | Full name of the passenger | String (used for title extraction) |
| `Sex` | Gender of the passenger | `male`, `female` |
| `Age` | Age in years | Fractional if less than 1; contains missing values |
| `SibSp` | Number of siblings / spouses aboard | Integer |
| `Parch` | Number of parents / children aboard | Integer |
| `Ticket` | Ticket number | Alphanumeric |
| `Fare` | Passenger fare | Continuous float |
| `Cabin` | Cabin number | Contains missing values |
| `Embarked` | Port of embarkation | `C` = Cherbourg, `Q` = Queenstown, `S` = Southampton |

---

## 🛠️ Tech Stack & Libraries

- **Language:** Python
- **Data Manipulation:** `pandas`, `numpy`
- **Visualization:** `matplotlib`, `seaborn`
- **Machine Learning:** `scikit-learn` (Logistic Regression, Random Forest, Decision Trees, Support Vector Machines)

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone [https://github.com/Sumit70378/Titanic_Project.git](https://github.com/Sumit70378/Titanic_Project.git)
cd Titanic_Project

## 2. Set Up a Virtual Environment

# macOS/Linux
python3 -m venv venv
source venv/bin/activate

# Windows
python -m venv venv
venv\Scripts\activate

3. Install Dependencies

pip install -r requirements.txt

4. Run the Project

jupyter notebook
