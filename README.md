🏠 EAS503 Project: Airbnb Analysis
This repository contains the final project for the EAS503 Data Science course at the University at Buffalo. The project focuses on analyzing Airbnb listings across U.S. cities, with a particular emphasis on New York City. The analysis encompasses exploratory data analysis (EDA), predictive modeling, and the integration of external datasets to provide insights into pricing trends, availability, and the impact of external factors such as COVID-19 and crime rates.​
mohamedirfansh.github.io

📁 Project Structure
perl
Copy
Edit
EAS503_Project_AIRBNB_Analysis/
├── AIRBNB_ANALYSIS.ipynb
├── Covid19.ipynb
├── NY_Crime_Countywise.ipynb
├── median_household_income.ipynb
├── postal.ipynb
├── AB_US_2020.csv
├── 2020-county-index-rates.csv
├── United_States_COVID-19_Cases_and_Deaths_by_State_over_Time.csv
├── median_household_income.csv
├── room_type.csv
├── airbnb_new_data.tsv
├── univ_list_ny_new.tsv
├── university_list_ny.csv
├── us_census_bureau_regions_and_divisions.csv
├── airbnb.db
├── Covid19.db
├── income.db
├── postal.db
├── airbnb_logo.jpg
└── README.md
📊 Key Components
1. AIRBNB_ANALYSIS.ipynb
This notebook serves as the core analysis, performing:​

Data Cleaning & Preprocessing: Handling missing values, encoding categorical variables, and preparing the dataset for analysis.

Exploratory Data Analysis (EDA): Visualizing distributions, correlations, and trends in the Airbnb listings data.

Predictive Modeling: Implementing machine learning models such as Ridge Regression and Random Forest to predict listing prices.

Model Evaluation: Assessing model performance using metrics like Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R² score.​
mohamedirfansh.github.io
mohamedirfansh.github.io
+5
GeeksforGeeks
+5
pages.github.coecis.cornell.edu
+5
imonikheayeni.github.io
+1
pages.github.coecis.cornell.edu
+1

2. Covid19.ipynb
Analyzes the impact of the COVID-19 pandemic on Airbnb listings, incorporating data on case numbers and deaths to assess correlations with booking trends and availability.​

3. NY_Crime_Countywise.ipynb
Examines crime statistics across New York counties to determine potential influences on Airbnb listing performance and pricing.​

4. median_household_income.ipynb
Investigates the relationship between median household income levels and Airbnb listing characteristics, exploring socioeconomic factors affecting the Airbnb market.​

5. postal.ipynb
Processes and analyzes postal code data to enhance the geographical granularity of the analysis, facilitating more localized insights.​

📂 Datasets
AB_US_2020.csv: Primary dataset containing Airbnb listings across U.S. cities.

2020-county-index-rates.csv: County-level index rates for various socioeconomic indicators.

United_States_COVID-19_Cases_and_Deaths_by_State_over_Time.csv: Time-series data on COVID-19 cases and deaths.

median_household_income.csv: Data on median household incomes across different regions.

room_type.csv: Information on different room types available in Airbnb listings.

airbnb_new_data.tsv: Supplementary Airbnb data for extended analysis.

univ_list_ny_new.tsv & university_list_ny.csv: Lists of universities in New York, used to assess the impact of nearby educational institutions on Airbnb listings.

us_census_bureau_regions_and_divisions.csv: Census data for regional analysis.​
GeeksforGeeks
locdam.github.io

🧪 Methodology
Data Integration: Combining multiple datasets to enrich the analysis and provide multifaceted insights.

Feature Engineering: Creating new features to capture complex relationships within the data.

Modeling: Applying machine learning algorithms to predict listing prices and understand key influencing factors.

Visualization: Utilizing plots and charts to communicate findings effectively.​
imonikheayeni.github.io
pages.github.coecis.cornell.edu
+1
imonikheayeni.github.io
+1
envaldy.github.io

📈 Results
Random Forest Model: Achieved superior performance in predicting listing prices, with lower MAE and RMSE compared to Ridge Regression.

Key Influencers: Identified neighborhood group, room type, and minimum nights as significant predictors of price.

COVID-19 Impact: Observed a decline in listings and bookings correlating with the rise in COVID-19 cases.

Crime Rates: Higher crime rates in certain counties were associated with lower Airbnb activity.​
GeeksforGeeks
+2
imonikheayeni.github.io
+2
pages.github.coecis.cornell.edu
+2

🔧 How to Run
Clone the Repository:

bash
Copy
Edit
git clone https://github.com/ddangwal1909/EAS503_Project_AIRBNB_Analysis.git
Navigate to the Directory:

bash
Copy
Edit
cd EAS503_Project_AIRBNB_Analysis
Install Dependencies: Ensure you have the necessary Python libraries installed:

bash
Copy
Edit
pip install pandas numpy matplotlib seaborn scikit-learn
Run Notebooks: Open the notebooks using Jupyter Notebook or any compatible IDE and execute the cells sequentially.

📚 References
Airbnb Open Data

U.S. Census Bureau

Johns Hopkins COVID-19 Data Repository

New York State Crime Statistics​

📌 Notes
This project is for educational purposes as part of the EAS503 Data Science course.

Data privacy and ethical considerations have been maintained throughout the analysis.​
mohamedirfansh.github.io



