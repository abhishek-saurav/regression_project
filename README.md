Project Overview
In this project, we explore the relationship between advertisement spending across various channels (TV, Radio, Newspaper) and sales outcomes. Our objective is to identify the most effective advertisement medium to optimize marketing budget allocation for maximizing sales revenue.

Problem Statement
As a Marketing Manager, the goal is to increase sales by strategically increasing advertisement spending. We aim to uncover which advertisement mode is the most effective in driving sales, ensuring an optimal allocation of the advertising budget.

Data Description
The dataset consists of 200 observations with the following columns:

TV: Advertising dollars spent on TV for a single product in a given market (in thousands of dollars).
Radio: Advertising dollars spent on Radio.
Newspaper: Advertising dollars spent on Newspaper.
Sales: Sales of a single product in a given market (in thousands of widgets).
Methodology
The analysis involves:

Data Preprocessing: Handling outliers, missing values, and scaling features.
Exploratory Data Analysis (EDA): Visualizing the data to understand relationships between advertisement spends and sales.
Model Building: Using linear regression to model the impact of advertisement spends on sales.
Model Evaluation: Assessing the model's performance with R² metric, residual analysis, and prediction accuracy on a test set.
Key Findings
TV advertisement spending has the highest correlation with sales, suggesting it's the most effective channel for driving sales.
The linear regression model incorporating TV and Radio advertisement spends as predictors explained approximately 90% of the variance in sales.
The final model formula: Sales = 3.231772 + 12.436614 * TV + 9.986861 * Radio
Installation and Usage
Clone the repository and navigate to the project directory. The analysis is provided in a Jupyter Notebook (Advertisement Case Study-Copy1.ipynb) and a Python script (Advertisement Case Study-Copy1-3.py).

Prerequisites
Python 3.x
Jupyter Notebook or an IDE that supports .ipynb and .py files.
Required Python libraries: pandas, numpy, matplotlib, seaborn, statsmodels, sklearn
To install the required Python libraries, run:

Copy code
pip install -r requirements.txt
Contributing
Feel free to fork the project and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

License
This project is open-source and available under the MIT License.
