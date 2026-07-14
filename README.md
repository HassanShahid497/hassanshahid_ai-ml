# Used Car Price Prediction - Milestone 1

This repository contains the first milestone of our Machine Learning project, focusing on data preparation, exploratory data analysis, and preprocessing for a Used Car Price Prediction engine.

## Project Structure
* `data_preprocessing.ipynb`: The complete preprocessing pipeline (data cleaning, imputation, encoding, scaling).
* `car_data.csv`: The clean CarDekho dataset used for training and testing.
* `README.md`: Project documentation and setup instructions.

## Preprocessing Steps Implemented
1. **Data Cleaning:** Handled duplicate records and set up robust median imputation.
2. **Feature Engineering:** Extracted `Vehicle_Age` from the manufacturing year to improve model signal.
3. **Outlier Treatment:** Implemented IQR capping on high-variance numerical columns.
4. **Categorical Encoding:** Converted nominal variables to mathematical representations using One-Hot Encoding.
5. **Feature Scaling:** Applied `StandardScaler` to normalize features for distance-sensitive algorithms.

## How to Run
1. Clone this repository:
   ```bash
   git clone <your-github-repo-link>