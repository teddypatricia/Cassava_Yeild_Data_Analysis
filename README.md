Cassava Yield Data Analysis
This project analyzes cassava yield data using Python and Jupyter Notebook. The work includes data cleaning, exploratory analysis, statistical testing, association rule mining, and predictive modeling to support farmers and policymakers.

Tasks Completed
1. Data Exploration & Cleaning
Checked distributions for all variables
Handled missing values (median/mode)
Treated outliers using IQR method
Produced a cleaned dataset

2. Statistical Relationship Analysis
Two continuous variables: scatterplot + Pearson correlation
Continuous vs categorical: boxplots + ANOVA
Two categorical variables: crosstabs + Chi-square test

3. Farmer-Focused Questions
Tested whether fertilizer affects yield
Tested whether tillage method affects yield
Used ANOVA/t-tests + visualizations

4. Association Rule Mining
Used Apriori algorithm to find seasonal patterns in fertilizer use
Interpreted rules using support, confidence, and lift

6. Predictive Modeling
Built a model for Plants_harvested
Evaluated performance using R², RMSE, and cross-validation

Tools Used
Python, Jupyter Notebook, Pandas, NumPy, Matplotlib, Seaborn, SciPy, Scikit-learn, Mlxtend.

Running the Notebook
pip install pandas numpy matplotlib seaborn scipy scikit-learn mlxtend
jupyter notebook

Remarks

The analysis provides insight into yield patterns and shows that fertilizer and tillage had limited statistical impact in this dataset. The predictive model performed strongly and can support planning and decision-making.
