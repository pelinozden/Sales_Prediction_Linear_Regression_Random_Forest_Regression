# Sales_Prediction_Linear_Regression_Random_Forest_Regression

This repository contains the code and analysis for a sales prediction project. The project utilizes a dataset obtained from Kaggle, which can be found [here](https://www.kaggle.com/datasets/harrimansaragih/dummy-advertising-and-sales-data).

## Project Overview

The main goal of this project is to predict sales based on advertising data. The following steps were performed:

1. **Exploratory Data Analysis (EDA):** A thorough exploration of the dataset was conducted to understand its structure and characteristics.

2. **Data Preprocessing:** The dataset underwent preprocessing to handle missing values, encode categorical variables, and scale numerical features.

3. **Data Visualization:** Various visualizations were created to gain insights into the relationships between different variables in the dataset.

4. **Model Building:**
   - **Linear Regression:** A linear regression model was implemented to predict sales based on the features in the dataset.
   - **Random Forest Regression:** A random forest regression model was also trained and evaluated for comparison.

5. **Results Comparison:** The results of the linear regression and random forest regression models were compared to determine the effectiveness of each model in predicting sales.

## Getting Started

To replicate or further explore the analysis, follow these steps:

```bash
# 1. Clone the repository:
git clone https://github.com/pelinozden/Sales_Prediction_Linear_Regression_Random_Forest_Regression.git

# 2. Navigate to the project directory:
cd Sales_Prediction_Linear_Regression_Random_Forest_Regression

# 3. Activate your Anaconda environment (if using one):
conda activate your_environment_name
# Replace "your_environment_name" with your actual environment name.

# 4. List the required libraries and versions:
conda list --export > requirements.txt

# 5. Check the created requirements.txt file:
# You can use any text editor or the cat command on Linux/Mac.
# For example:
cat requirements.txt   # or open requirements.txt (on Windows)

# 6. Install the dependencies from requirements.txt:
conda install --file requirements.txt

## Dataset Information

The dataset used in this project can be found on Kaggle [here](https://www.kaggle.com/datasets/harrimansaragih/dummy-advertising-and-sales-data). Make sure to download it and place it in the `data/` directory before running the notebook.

## Conclusion

This project demonstrates the process of exploring, analyzing, and predicting sales based on advertising data. The comparison of linear regression and random forest regression models provides insights into the predictive performance of each approach.

For any questions or suggestions, feel free to open an issue or contact me.

Happy coding!
