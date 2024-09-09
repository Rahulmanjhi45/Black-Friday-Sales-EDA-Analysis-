# Black Friday Sales EDA Analysis

## Project Overview
This project provides an Exploratory Data Analysis (EDA) on a Black Friday sales dataset. The objective is to understand customer purchase behavior by analyzing different factors such as gender, age, occupation, city, and product categories. The analysis includes handling missing data, data cleaning, visualization, and insights generation.

##  Dataset
The dataset used for this analysis contains information on customer demographics, product categories, and purchase amounts during Black Friday sales. Some of the key features in the dataset include:

1. User_ID:-  Unique customer ID  
2. Product_ID:-  Unique product ID  
3. Gender:-  Gender of the customer (Male/Female)  
4. Age:-  Age group of the customer (e.g., 0-17, 18-25, 26-35, etc.)  
5. Occupation:-  Occupation category of the customer  
6. City_Category:-  City type (A, B, or C)  
7. Stay_In_Current_City_Years:-  Duration of the customer's stay in the current city  
8. Product_Category_1, Product_Category_2, Product_Category_3:-  Categories of products purchased  
9. Purchase:-  Purchase amount


## Project Structure

black-friday-sales-eda-analysis/  
├── data/  
│   └── BlackFridaySales.csv          # Dataset file  
├── notebooks/  
│   └── black_friday_sales_analysis.ipynb   # Jupyter notebook with the analysis  
├── src/  
│   └── data_cleaning.py              # Data cleaning script  
│   └── data_visualization.py         # Data visualization script  
├── README.md                         # Project overview  
└── requirements.txt                  # Python dependencies  


## Installation

1. Clone the repository:  
  git clone https://github.com/yourusername/black-friday-sales-eda-analysis.git
  cd black-friday-sales-eda-analysis

2. Set up a virtual environment (optional but recommended):
  python3 -m venv venv
  source venv/bin/activate   # On Windows: venv\Scripts\activate

3. Install dependencies:
  pip install -r requirements.txt

4. Run the Jupyter Notebook: Open the notebook in your favorite editor (e.g., JupyterLab) and run the cells to execute the analysis.


## Analysis Workflow
The analysis is broken down into several steps:

1. Importing Libraries: Import the necessary Python libraries such as pandas, seaborn, and matplotlib for data manipulation and visualization.  
2. Loading the Dataset: Load the dataset from a CSV file using pandas.  
3. Data Cleaning: Handle missing values in Product_Category_2 and Product_Category_3 by imputing them with -1.
4. #### Exploratory Data Analysis:
   Distribution of numerical features (e.g., purchase amounts, product categories).  
   Distribution of categorical features (e.g., gender, age, city category).  
   Purchase patterns across gender, age, and city categories.  
5. Data Visualization: Generate histograms, bar plots, boxplots, and heatmaps to explore correlations and trends.
6. #### Insights:
   Average purchase behavior by gender and age.  
   Popular product categories.  
   Analysis of purchase behavior across city types and occupations.


## Key Insights
  1. Purchase Behavior by Gender: Males tend to have higher average purchase amounts than females.  
  2. Purchase Behavior by Age: The age group 51-55 shows the highest average purchase amount, followed by 55+.  
  3. City-wise Purchase: City Category C has the highest average purchase amount, followed by B and A.  
  4. Product Preferences by Gender: Product Category 3 is more popular among males, while females tend to purchase more from Product Category 1 and 2.  

## Visualizations

  1. Histograms: Visualizing the distribution of numerical features such as Purchase, Product_Category_1, Product_Category_2, and Product_Category_3.
  2. Bar Charts and Pie Charts: Understanding the distribution of categorical features such as Gender, Age, and City_Category.
  3. Boxplots: Comparing purchase behavior across different groups.
  4. Correlation Matrix: Analyzing the relationships between product categories and purchase amounts.

## Conclusion

This EDA on Black Friday Sales data provides valuable insights into customer demographics, purchase behavior, and product preferences. These insights can help businesses tailor marketing strategies and improve customer targeting for future Black Friday sales events.

## Future Work
1. Feature engineering to create new variables based on the dataset.
2. Machine learning models to predict customer purchase amounts.
3. Further investigation into product recommendation systems based on the data.


