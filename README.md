📊 Netflix Movies & TV Shows Analysis – Power BI Project
📌 Project Overview

This project analyzes Netflix Movies and TV Shows data to identify trends in content distribution, genres, ratings, and global availability. The dataset was cleaned using Excel and Power Query, and interactive visualizations were created in Power BI to transform raw data into meaningful insights.

🎯 Objectives
- Analyze the distribution of Movies vs TV Shows
- Identify content release trends over the years
- Explore genre and rating patterns
- Perform country-wise content analysis
- Build an interactive dashboard for insights

🛠️ Tools & Technologies Used
- Microsoft Excel – Data cleaning and preprocessing
- Power Query – Data transformation
- Power BI Desktop – Data modeling and visualization

📂 Dataset Information
Source: Public Netflix dataset (https://www.data4ecology.org/)

The dataset includes:
* Title
* Content Type (Movie / TV Show)
* Director & Cast
* Country
* Release Year
* Rating
* Duration
* Genres
* Date Added
* Description

🔄 Data Cleaning & Preparation (Excel)
- Assigned appropriate data types to all columns
- Removed unnecessary columns and empty rows
- Trimmed and cleaned text fields for consistency
- Corrected a small number of records where data entries were misaligned in the source data
- Handled missing values:
    * Replaced missing text fields with "Information Not Available"
    * Replaced missing ratings with "NR"
    * Retained null date/year values due to data limitations
- Split the duration column into:
    * duration_value
    * duration_type
- Standardized categorical fields such as genres and duration units
- Checked for duplicate records and verified data integrity

📊 Power BI Data Modeling
- Imported cleaned dataset into Power BI
- Verified data types for accurate analysis
- Created a reference table (Netflix_Country) to properly analyze multi-country entries
- Established relationships between the main dataset and the country reference table
- Used built-in aggregation features for visualization

📈 Dashboard Features
The interactive Power BI dashboard includes:
  - KPI cards showing total titles and content distribution
  - Bar charts for genre and country analysis
  - Line charts showing content release trends over time
  - Pie charts for rating distribution
  - Slicers for filtering by year, genre, and content type

🔍 Key Insights
- Movies make up the majority of Netflix content compared to TV Shows
- Content additions increased significantly after 2015
- A few genres dominate Netflix’s content library
- The United States contributes the highest number of titles
- TV Shows tend to have higher maturity ratings than Movies

📁 Repository Contents

•	Netflix_Movies_and_TV_Shows.csv – Original uncleaned dataset
•	Netflix_Movies_and_TV_Shows_Cleaned.xlsx – Cleaned dataset.
•	Netflix_Movies_and_TV_Shows_Report.pbix – Power BI dashboard file.
•	Netflix_Project_Documentation.pdf – Project documentation.

📄 Detailed Project Documentation
The complete project report, including detailed methodology, cleaning steps, and analysis, is available below:

👉 Download Full Project Documentation : (Netflix_Project_Documentation.pdf)

🚀 How to Use
- Download the dataset file to view cleaned data
- Open the .pbix file using Power BI Desktop
- Use slicers in the dashboard to explore insights interactively

💡 Skills Demonstrated
- Data Cleaning & Preparation
- Data Transformation
- Data Modeling
- Data Visualization
- Dashboard Design
- Analytical Thinking

👤 Author
Suhana Mukthar
Aspiring Data Analyst | Former Software Engineer
Skilled in Excel, Power BI & Python


