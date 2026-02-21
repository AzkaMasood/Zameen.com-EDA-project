Pakistan Real Estate Market Analysis
Exploratory Data Analysis (EDA) using Python

Project Overview

This project presents a comprehensive Exploratory Data Analysis (EDA) of Pakistan’s real estate market using property listing data from Zameen.com.

The objective is to uncover:
Market trends
City-wise pricing differences
Property type distribution
Luxury market growth
Key pricing determinants
The analysis was conducted using Python in Google Colab.

🎯 Project Objectives
Clean and preprocess real-world real estate data
Engineer meaningful features (e.g., area conversion to marla)
Detect and analyze outliers
Perform univariate, bivariate, and multivariate analysis
Answer key business questions using visualization
Generate actionable business insights

📂 Dataset Description
The dataset contains ~190,000+ property listings and includes:

Column	Description
property_id	Unique property identifier
property_type	Type of property (House, Flat, etc.)
price	Listing price (PKR)
city	City name
province_name	Province
baths	Number of bathrooms
bedrooms	Number of bedrooms
area	Property size (Mixed units: Kanal / Marla)
purpose	For Sale / For Rent
agency	Real estate agency
agent	Individual agent
date_added	Listing date

🛠 Tools & Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Google Colab

🔧 Data Cleaning & Feature Engineering
✔ Handled Non-Standard CSV Format
Loaded dataset using semicolon delimiter
✔ Missing Value Treatment
Checked all categorical and numerical columns
Applied appropriate imputation strategy where necessary
✔ Area Conversion
The area column contained mixed units:
1 Kanal = 20 Marla
Converted all values into a new column: area_in_marla
✔ Date Feature Extraction
Extracted Year and Month from date_added for time-based analysis

📊 Exploratory Data Analysis
🔹 Univariate Analysis
Price distribution (Right-skewed)
Property type distribution
City-wise listing representation
Area size distribution

🔹 Bivariate Analysis
Price vs Area
Price vs Bedrooms
Price comparison across cities
Seasonal listing trends

🔹 Multivariate Analysis
Correlation matrix
Price vs Area by City
Property type pricing by purpose
Luxury segment growth analysis

📈 Key Insights
Property prices are highly right-skewed with a growing luxury segment.
Lahore and Islamabad dominate the premium property market.
Area size has the strongest positive correlation with price.
Bedrooms and bathrooms significantly influence valuation.
Seasonal listing patterns suggest mid-year activity peaks.
A small number of agencies dominate high-value markets.
