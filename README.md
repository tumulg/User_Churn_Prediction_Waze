# Predicting User Churn for Waze

This project aims to predict user churn for Waze. Churn quantifies the number of users who have uninstalled the Waze app or stopped using it. The focus is on monthly user churn, and an accurate model will help prevent churn, improve user retention, and grow Waze’s business.

The project involves data analysis to uncover patterns in user behavior and machine learning to predict churn. These insights can help Waze enhance user experience and retention strategies.

## Project Overview

The project is divided into five Jupyter notebooks, each focusing on a specific aspect of the analysis and modeling:

1. **Inspection and Analysis**: Investigate and understand the Waze dataset.
2. **EDA and DataViz**: Data Cleaning and Exploratory Data Analysis.
3. **Stats and Hypothesis Testing**: To find out whether there is a statistically significant difference in the mean amount of rides between the two device type users.
4. **Binomial Logistic Regression Model**: To build a binomial logistic regression model to predict user churn on a variety of variables.
5. **Random Forest and XGBoost Models**: To predict whether or not a Waze user is retained or churned.

## Machine Learning

### Purpose
To identify factors influencing user churn and generate actionable insights for Waze to enhance user retention.

### Goal
To predict whether a user is likely to churn based on behavioral and usage data.

## Technologies Used

- **Programming Language**: Python
- **Libraries**:
  - Data Manipulation: Pandas, NumPy
  - Visualization: Matplotlib, Seaborn
  - Machine Learning: Scikit-learn, XGBoost
- **Development Environment**: Jupyter Notebooks

## Dataset Description

The dataset used for this project is `waze_dataset.csv`. It contains synthetic data created in collaboration with Waze. The dataset includes the following columns:

| Column Name               | Type   | Description                                                         |
|---------------------------|--------|---------------------------------------------------------------------|
| label                     | Object | Binary target variable (“retained” vs “churned”) indicating user churn. |
| sessions                  | Int    | Number of times a user opened the app during the month.            |
| drives                    | Int    | Number of drives (at least 1 km) during the month.                 |
| device                    | Object | Type of device a user starts a session with.                       |
| total_sessions            | Float  | Estimated total sessions since a user onboarded.                   |
| n_days_after_onboarding   | Int    | Days since a user signed up for the app.                           |
| total_navigations_fav1    | Int    | Total navigations to favorite place 1 since onboarding.            |
| total_navigations_fav2    | Int    | Total navigations to favorite place 2 since onboarding.            |
| driven_km_drives          | Float  | Total kilometers driven during the month.                          |
| duration_minutes_drives   | Float  | Total duration driven in minutes during the month.                 |
| activity_days             | Int    | Number of days the user opened the app during the month.           |
| driving_days              | Int    | Number of days the user drove (at least 1 km) during the month.    |

## Usage

To run the notebooks:

1. Open your terminal and navigate to the project directory.
2. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```
3. Open and run the notebooks in the following order:
   - **Inspection and Analysis**
   - **EDA and DataViz**
   - **Stats and Hypothesis Testing**
   - **Binomial Logistic Regression Model**
   - **Random Forest and XGBoost Models**

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments

- Waze for supporting the creation of the synthetic dataset.
- The Python and data science community for valuable resources and tools.
