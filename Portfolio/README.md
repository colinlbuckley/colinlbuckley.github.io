# Data Science Portfolio

### Colin L. Buckley

## [Project 1: ACS Broadband Vignette](https://github.com/colinlbuckley/Steamcharts_Dashboard)
* Leveraged ACS data to create a preliminary proof-of-concept vignette visualizing county-level spatial trends in U.S. broadband access.  
* Built experience with ACS data structures, Census Bureau APIs, and relevant mapping packages in R.  
* Constructed a robust data visualization outline to facilitate a forthcoming quantitative analysis of broadband access against socioeconomic markers.  

![](/Portfolio/Images/acs_broadband_vignette_thumbnail.png)

## [Project 2: Steam Player Count Data - HTML Scraping and Dashboard](https://github.com/colinlbuckley/Steamcharts_Dashboard)
* Used {rvest} to scrape video game player count data from [Steamcharts](https://steamcharts.com/).  
* Implemented iterative HTML scraping functions in streamlined and well-documented code.  
* Employed {polite} to adhere to ethical web scraping standards and ensure compliance with the site's robots.txt file.  
* Performed necessary cleaning and engineering with {dplyr}.  
* Ensured reproducibility at all stages so that monthly time series data can be re-scraped and updated regularly.   
* Built and deployed a polished {shiny} dashboard to display final data.  
* Published dashboard on shinyapps.io [here](https://colinlbuckley.shinyapps.io/Steamcharts_Dashboard/).  

![](/Portfolio/Images/steamcharts_dashboard_screenshot.png)

## [Project 3: Exploratory Data Analysis for ML Feature Selection - Titanic Kaggle Competition](https://colinlbuckley.github.io/Titanic_EDA_Notebook)
* Explored Titanic passenger dataset with the aim of informing feature selection for Kaggle machine learning competition.  
* Examined broad data characteristics (size, shape, variables, etc.).  
* Performed visual EDA to explore univariate distributions and bivariate relationships between predictors and target variable.  
* Implemented basic feature engineering to improve predictive strength later on.  
* Investigated statistical relationships with preliminary multiple logistic regression model.  
* Built a polished HTML notebook with RMarkdown for publication.  
* Full repository available [here](https://github.com/colinlbuckley/Titanic_ML_Kaggle).  

![](/Portfolio/Images/Pclass_Survival_distribution.png)

## [Project 4: International COVID-19 Vaccination Progress Comparator](https://github.com/colinlbuckley/vaccination_progress_app)
* Created an interactive Shiny web application in R that reads in a global vaccination dataset and visualizes vaccination progress between up to eight countries at a time.  
* Built a simple UI with interactive inputs, allowing users to search for and select countries and dependent variables.  
* Coded a reactive ggplot2 visualization that compares time series data across countries.  
* Adapted an R script to pull regularly updated vaccine data from Kaggle.com.  
* Performed simple data cleaning and manipulation with dplyr.  
* Hosted the app on shinyapps.io [here](https://colinlbuckley.shinyapps.io/vaccine_progress_app/).  

![](/Portfolio/Images/g7_total_per_hundred.png)
