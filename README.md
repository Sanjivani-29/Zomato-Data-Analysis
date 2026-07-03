🍽️ Zomato Data Analysis using Python & Tableau
📌 Project Overview

This project focuses on analyzing restaurant data from Zomato to discover customer dining preferences and business insights. Using Exploratory Data Analysis (EDA) techniques in Python and interactive dashboards in Tableau, the project identifies trends related to restaurant ratings, cuisines, pricing, online ordering, and location.

The objective is to help restaurant owners, investors, and food businesses understand the factors that influence customer satisfaction and make data-driven business decisions.

📂 Dataset

The dataset contains information about 50,000+ restaurant listings collected from Zomato.

Features include:
Restaurant Name
City
Locality
Cuisines
Average Cost for Two
Price Range
Aggregate Rating
Votes
Online Order Availability
Table Booking Availability
Restaurant Type
🎯 Project Objectives
Perform data cleaning and preprocessing.
Conduct Exploratory Data Analysis (EDA).
Identify factors affecting restaurant ratings.
Analyze cuisine popularity across different cities.
Study pricing trends and customer preferences.
Evaluate the impact of online ordering and table booking.
Build an interactive Tableau dashboard for visualization.
🛠️ Technologies Used
Python
Pandas
NumPy
Matplotlib
Jupyter Notebook
Tableau
Git & GitHub
📊 Exploratory Data Analysis

The project includes the following analyses:

Data Cleaning
Removed duplicate records
Handled missing values
Standardized categorical values
Converted data types where required
Restaurant Distribution
Number of restaurants by city
Restaurant type distribution
Ratings Analysis
Rating distribution
Highly rated restaurants
Rating vs. Number of Votes
Cuisine Analysis
Most popular cuisines
Cuisine combinations
Cuisine-wise average ratings
Pricing Analysis
Average cost for two
Price range distribution
Cost vs. Ratings
Online Services Analysis
Online Order availability
Table Booking availability
Impact on customer ratings
Customer Preference Analysis
Votes vs. Ratings
Popular restaurant categories
High-performing restaurants
📈 Tableau Dashboard

An interactive Tableau dashboard was created to visualize:

Restaurant distribution by city
Cuisine popularity
Average ratings
Price range analysis
Online ordering trends
Customer voting patterns

The dashboard enables users to filter data dynamically and gain actionable business insights.

📁 Project Structure
Zomato-Data-Analysis/
│
├── Zomato_pbl.ipynb                 # Data cleaning and EDA notebook
├── zomato_outlet_final.csv          # Cleaned dataset
├── dashboard/
│   └── Zomato_Dashboard.twb
├── images/
│   ├── rating_distribution.png
│   ├── cuisine_analysis.png
│   ├── price_range.png
│   ├── correlation_heatmap.png
│   └── tableau_dashboard.png
├── requirements.txt
└── README.md
📌 Key Insights
Restaurants offering online ordering generally receive higher customer engagement.
Moderate pricing attracts a larger customer base compared to premium pricing.
Certain cuisines consistently receive higher ratings and popularity.
Restaurants with higher customer votes tend to maintain better ratings.
Location plays a significant role in restaurant popularity and customer preferences.
📊 Results
Successfully analyzed 50,000+ restaurant records.
Identified major factors influencing restaurant ratings.
Built an interactive Tableau dashboard for business decision-making.
Generated actionable insights for restaurant owners and investors.
🚀 Future Enhancements
Develop predictive models for restaurant ratings.
Implement recommendation systems for restaurants.
Deploy an interactive web application using Streamlit.
Integrate live restaurant data using APIs.
▶️ How to Run the Project
Clone the repository:
git clone https://github.com/your-username/Zomato-Data-Analysis.git
Navigate to the project directory:
cd Zomato-Data-Analysis
Install the required libraries:
pip install -r requirements.txt
Open the notebook:
jupyter notebook Zomato_pbl.ipynb
