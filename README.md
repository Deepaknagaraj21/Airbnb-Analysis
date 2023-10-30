# Airbnb-Analysis
Airbnb Analysis
Airbnb is an online marketplace that connects people who want to rent out their property with people who are looking for accommodations, typically for short stays. Airbnb offers hosts a relatively easy way to earn some income from their property.

Airbnb embarks on an extensive investigation of its own data. The impact of Airbnb on the travel and property management sectors has been transformative, emphasizing the significance of scrutinizing this data for valuable insights on pricing, availability trends, and location-specific patterns. This initiative leverages MongoDB Atlas, and advanced data visualization methods like Tableau, powerbi to deliver a thorough analysis.

Table of Contents

Key Technologies and Skills
Installation
Usage
Features
Contributing
License
Contact

Installation

To run this project, you need to install the following packages:

import pymongo
import pandas as pd
import dataprep.eda.create_report as report
pd.set_option('display.max_columns', None)
import numpy as np
import matplotlib.pyplot as plt     
%matplotlib inline
import seaborn as sns               
import warnings
warnings.filterwarnings('ignore')

Usage

To use this project, follow these steps:

Clone the repository: git clone https://github.com/Deepaknagaraj21/Airbnb-Analysis
Install the required packages: pip install -r requirements.txt

Data Compilation and Preparation

Retrieving MongoDB Data: Gather the Airbnb dataset from MongoDB for further examination.
Dealing with Null and Duplicate Entries: Apply preprocessing procedures to manage absent data and eliminate duplicates.
ETL and Data Frame Conversion: Execute Extract, Transform, Load (ETL) processes to reshape the data into organized data frames suitable for analysis.

Feature Examination

Property Analysis: Assess the total count of properties categorized by property type, room type, and bed type.
Duration of Stays: Investigate the typical minimum and maximum length of guest stays.
Cancellation Policy Evaluation: Understand how cancellation policies influence booking trends.
Accommodation Statistics: Explore metrics related to accommodates, bedrooms, and beds.
Review Scrutiny: Examine data on total reviews, average review scores, and the distribution of reviews.
Bathroom and Pricing Review: Analyze factors such as bathroom count, pricing, cleaning fees, and additional guest charges.
Guest Inclusion Patterns: Study the number of guests included in bookings.
Host Insights: Explore host-related metrics, including host response time, response rate, and the number of properties hosted.
Geographic Assessment: Investigate the geographic distribution of Airbnb listings at the market and country levels.
Availability Trends: Visualize property availability for the next 30, 60, 90, and 360 days.

Top Host Analysis

Identify and evaluate the top 10 hosts based on various criteria, providing insights into host performance and success.

Data Visualization

Leverage Plotly to craft interactive and informative visual representations for Exploratory Data Analysis (EDA), enhancing data exploration.

Tableau Dashboard

Construct an extensive Tableau dashboard for in-depth visual examination of Airbnb data, with a focus on average prices and the number of reviews based on country and room types.

For a deeper dive into insights, explore the Tableau dashboard at https://public.tableau.com/app/profile/deepak.n7502/vizzes
















