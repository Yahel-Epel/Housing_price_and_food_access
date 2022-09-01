# Housing Prices & Food Access

The purpose of the analysis is to understand the relationship between housing prices and access to food in California in 2015 and 2019. 

# Motivation
The motivation of this project is to identify when and where to buy/rent a home in the United States based food access.

1. This is how grocery chains affect a home’s value
https://www.housingwire.com/articles/49767-this-is-how-grocery-chains-affect-a-homes-value/

2. Does the New Whole Foods in Your Neighborhood Increase Your Home Value?
https://realestate.usnews.com/real-estate/articles/does-the-new-whole-foods-in-your-neighborhood-increase-your-home-value


# Questions we want to answer
- Does access to food sources impact housing prices in California?
  - Compared 2015 and 2019
- Which zip codes have the most organic grocery stores vs. fast food locations?
- How does our research inform our audience’s decision making?

# Machine Learning Questions:
- Can the model accurately identify a relationship between food access and housing prices in California?

# Tools/Modules we use:
- Data Acquisition and Cleaning 
  - Google Searches/API
  - Web Scraping
  - Python/ Jupyter Notebook/Pandas
- Data Management
  - SQL/SQLite
- Machine Learning
  - Supervised Learning 
- Data Visualization 
  - Tableau
  - HTML

# Results
## Machine Learning: 
### Machine Model Results 2015
![Machine_model_results_2015.png](Images\Machine_model_results_2015.png)

### Machine Model Results 2019
![Machine_model_results_2019.png](Images\Machine_model_results_2019.png)

## Data Visualization:
- Organic grocery stores: 
  - Zip Codes with more Organic grocery stores: 94103, 91105, 90046, 90036
  - 3 of these zip codes are in LA county and one in SF county. 
  - The median house value for these zip codes is $1.72M 
 
- Zip codes with more fast food locations
  - There are 66 zip codes with 2 fast food locations. 
  - The median house value for these zip codes is $850K

### The median house value next to more organic grocery stores is double than the house value next to location with more fast food.  
![Data_Visualization.png](Images\Data_Visualization.png)

[Housing Prices and Food Access website](https://yahel-epel.github.io/Housing_price_and_food_access_html/)

Tableau: 

[Interactive Data Visualization](https://public.tableau.com/views/InteractiveDataVisualization_16543674107880/DashboardFront?:language=en-US&:display_count=n&:origin=viz_share_link)

[Housing Values by Food Type dashboard](https://public.tableau.com/views/Dashboard_16542010278120/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link)

# Conclusion & Limitations
- 77% of food access accessibility explains housing prices in California in 2015
- 65% for 2019 (Neural Networking)

### Limitations
- Cannot establish a strong relationship 
- Outdated data 
- Analysis does not include other confounding factors 
  - Ex: Date of opening of Whole Foods and Trader Joe’s

# Recommendations/ Key Lessons Learned
- Food accessibility thought to be focused on distance, but it actually encompasses a combination of variables.
- Future analyses should review:
  - Housing price changes over time. Include data from multiple years.
  - Other demographic data like median household income, poverty rate, school district, race and ethnicity, location of corporate business 
  - Interest rate
  - Migration data
- Have more complete datasets that can be merged to provide a comprehensive understanding

# Data Sources
- Low Food Access- https://www.ers.usda.gov/data-products/food-access-research-atlas/download-the-data/
- Housing Prices- Zillow/ US Census
- Whole Foods, Trader Joe’s, Burger King & McDonald’s locations-  Google API and Geopy





