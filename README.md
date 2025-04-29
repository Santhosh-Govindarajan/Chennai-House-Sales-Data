📋 Project Overview
This project analyzes the Chennai real estate market using historical sales data.
By performing data cleaning and  statistical exploration, we aim to discover key insights that can help understand property price drivers in Chennai.
🛠️ Tools Used
•	Python 3
•	Jupyter Notebook
•	Pandas — for data manipulation
•	Scikit-learn — for simple preprocessing
🧹 Data Cleaning
The raw dataset (train-chennai-sale.csv) contained:
•	Duplicated or inconsistent entries (e.g., redundant spaces, capitalization issues).
Cleaning steps included:
•	Dropping columns with excessive missing values.
•	Filling missing values with reasonable estimates (e.g., median or mean).
•	Converting categorical features to a consistent format.
📊 Exploratory Data Analysis (EDA)
Several statistical and visual techniques were applied:
•	Distribution analysis for variables like Area, Sale_Price, and Build_Up_Area.
•	Correlation heatmaps to identify which features influence the sale price most.
•	Scatter plots and box plots to visually inspect relationships between variables.
•	Outlier detection to handle extreme values in sale price and property size.
Key observations:
•	Sale Price generally increases with Area but with notable outliers.
•	Certain localities show significantly higher average sale prices.
•	Age of property inversely correlates with Sale Price in many cases.
📈 Statistics and Insights
•	Average Sale Price: ₹10894909.64 (based on dataset calculations)
•	Top 5 expensive localities: Below Listed PRT_ID’s are the top 5 expensie localities based on SALES_PRICE  
o	P08983
o	P02996
o	P00067
o	P09293
o	P09521
•	Feature Importance: Area and Locality were among the top influencing features.
📂 Repository Structure
/ChennaiSales.ipynb   # Jupyter Notebook with all analyses
/train-chennai-sale.csv # Raw data file
/README.md             # Project documentation
/ChennaiSale.csv      #Cleaned file without encoding
