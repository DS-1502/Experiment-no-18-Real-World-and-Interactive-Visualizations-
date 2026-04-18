# Experiment – 19 & 20

## Title  
COVID-19 Data Analysis and Visualization using Python



**Name:** Dhvan Shah  
**PRN:** 25070123042  
**Batch:** ENTC A2 (2025–2029)



## Aim  
- To analyze COVID-19 dataset using Python  
- To perform data preprocessing and visualization  



## Objectives  
- To understand real-world dataset handling  
- To clean and preprocess the dataset  
- To perform country-wise statistical analysis  
- To visualize data using maps and charts  



## Theory  

### 1. Introduction to Data Analysis
- Data analysis involves collecting, inspecting, cleaning,  
  and transforming data to obtain useful insights.  
- It helps in identifying patterns, trends, and relationships.  
- Python is widely used for data analysis because of its  
  powerful libraries and easy syntax.  



### 2. Dataset Description
- The dataset contains COVID-19 records from different countries.  
- Main columns included are:

  - Observation Date  
  - Province/State  
  - Country/Region  
  - Confirmed Cases  
  - Deaths  
  - Recovered Cases  

- Such datasets are used for pandemic monitoring and forecasting.  



### 3. Data Preprocessing
Data preprocessing is necessary to improve data quality.

Steps performed:

- Removing unnecessary columns such as:
  - `SNo`
  - `Last Update`

- Checking dataset information using `info()`  
- Detecting missing values  
- Converting data types:

  - Date column → datetime format  
  - Numerical columns → integer format  

- Rechecking cleaned dataset structure  



### 4. Feature Engineering
- A new column called **Active Cases** is created.

Formula used:

Active Cases = Confirmed − Deaths − Recovered

- This helps determine currently infected patients.  



### 5. Exploratory Data Analysis
The dataset is analyzed using different operations:

- Viewing first rows using `head()`  
- Checking shape of dataset  
- Extracting latest available date  
- Filtering latest records  
- Counting total countries present  
- Sorting and grouping data country-wise  



### 6. Country-wise Analysis
- Total confirmed, deaths, recovered, and active cases  
  are calculated for each country.  
- Specific countries such as India and Russia  
  are filtered for comparison.  
- Top affected countries are identified.  



### 7. Data Visualization

**Choropleth Map**
- Created using Plotly  
- Displays confirmed cases across world map  
- Darker color indicates higher cases  

**Top Countries Report**
- Shows countries with highest confirmed cases  
- Helps compare global impact  



### 8. Python Libraries Used

- **Pandas**
  - Data loading and preprocessing  

- **NumPy**
  - Numerical calculations  

- **Plotly**
  - Interactive charts and maps  



## Conclusion  
- This experiment demonstrates real-world data analysis  
  using Python on COVID-19 dataset.  
- Data preprocessing improves reliability of results.  
- Country-wise statistics help understand pandemic spread.  
- Visualization techniques make global trends easy to interpret.  
- Python is highly effective for practical data science tasks.
