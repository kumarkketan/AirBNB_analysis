I have done an Exploratory Data Analysis (EDA) on an Airbnb dataset to uncover key insights, understand patterns in listings, and prepare the data for potential further analysis or visualization. The goal of this analysis is to explore the Airbnb dataset, clean and preprocess the data, and extract meaningful insights about property types, pricing, locations, and customer reviews.

**Data Cleaning**

The dataset underwent a thorough cleaning process, including:

 • Handling missing values
 
 • Removing duplicates
 
 • Converting data types (e.g., price and date fields)
 
 • Filling null values based on longititude and longtitude using geopy.geocoders library
 
 • Standardizing column names
 
 • Filtering outliers (e.g., extremely high prices or long minimum nights)

**Tools & Libraries Used**

 • Python
 
 • Pandas
 
 • NumPy
 
 • Matplotlib

**Keywords Used for EDA**

 • info(), describe(), shape, isnull(), sum()
 
 • Data type conversion using astype()
 
 • Handling missing values with fillna(), dropna()
 
 • Value counts using value_counts()
 
 • Sorting and filtering with sort_values(), loc[], iloc[]
 
 • Grouping and aggregation using groupby(), agg()

**Visualizations:** hist(), boxplot(), scatterplot(), barplot()

**Key Insights**

 • Distribution of listing types and availability
 
 • Most and least expensive neighborhoods
 
 • Correlation between number of reviews and ratings
 
 • Popular room types and average prices
