# 🎬 Netflix Data Analysis & Dashboard

## 📌 Project Overview
This project explores a comprehensive dataset of Netflix titles (movies and TV shows) to uncover trends in content strategy, regional focus, and genre popularity. The final output is an interactive Excel dashboard that visualizes key metrics, providing a clear view of how Netflix has grown and diversified its catalog.

## 🛠️ Tools Used
* **Microsoft Excel:** Data cleaning, Pivot Tables, and Dashboard creation.
* **Data Visualization:** Advanced Excel charting, slicers, and conditional formatting.

## 📊 The Dashboard
*(Note: Upload a screenshot of your final Excel dashboard to an `images` folder and link it below)*
![Netflix Dashboard Preview](images/dashboard_screenshot.png)

### Key Features:
* **Content Split:** Visualization of the Movie vs. TV Show ratio on the platform.
* **Trend Over Time:** Analysis of content added to Netflix by year.
* **Geographic Insights:** Breakdown of the top content-producing countries.
* **Target Audience:** Distribution of content ratings (e.g., TV-MA, PG-13).

## 🧹 Data Cleaning & Preparation
The raw dataset (`netflix_titles.csv`) was processed before analysis:
* Addressed missing values in the `director`, `cast`, and `country` columns.
* Formatted the `date_added` column to extract specific years and months for time-series analysis.
* Cleaned the `listed_in` column to properly categorize and analyze individual genres.

## 💡 Key Insights
* **Content Dominance:** Movies make up the majority of the platform's historical catalog, but TV Shows have seen a significant spike in recent years.
* **Target Demographics:** A large portion of the platform's content is rated TV-MA, indicating a strong strategic focus on mature audiences.
* **Global Reach:** The United States and India are the leading producers of content on the platform.
* *(Add any other specific insights you found from your pivot tables here!)*

## 📂 Repository Structure
* `data/` - Contains the raw `netflix_titles.csv` dataset.
* `dashboard/` - Contains the final interactive `.xlsx` dashboard file.
* `images/` - Screenshots of the dashboard and charts.
* `README.md` - Project documentation.

## 🚀 How to Use This Project
1. Clone this repository or download the ZIP file.
2. Navigate to the `dashboard/` folder.
3. Open the `.xlsx` file in Microsoft Excel.
4. Use the built-in slicers to interact with the data and filter by year, rating, or country.
