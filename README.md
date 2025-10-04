📊 **Netflix Data Analysis with Power BI**

This project is an **Exploratory Data Analysis (EDA)** on the Netflix dataset using **Power BI**. The goal was to clean, transform, and analyze the data to gain insights into movies and TV shows, while also practicing different Power BI functionalities.

🚀 **Key Learnings & Transformations**

**Data Cleaning**

* Handled missing values in *director*, *cast*, and *country* columns (used placeholders like “No Information” and “Missing_Country”).
* Formatted *date_added* using Locale settings to remove errors.

**Column Transformations**

* Extracted numeric values from *duration* into two new columns:

  * `duration_minutes` (for movies)
  * `duration_seasons` (for TV shows)

**Category Mapping**

* Split comma-separated categories into a new table (`category_mapping`) with two columns:

  * `show_id`
  * `category`
* Enabled easy filtering and analysis by category.

**Text Processing**

* Converted *description* column to lowercase for better filtering.
* Created a custom column `murder-mystery` using conditional logic:

  * If *description* contains words like *death*, *kill*, *murder* → `Yes`
  * Otherwise → `No`

---

🧠 **Skills Practiced**

* Power Query Editor
* Column profiling and data cleaning
* Custom columns & conditional logic
* Splitting and restructuring tables
* Data modeling in Power BI

---

📈 **Visualizations Created**

**Page 1 – Content Overview**

* KPI Cards: Total Titles, Total Movies, Total TV Shows, Average Movie Duration
* Tree Map: Content distribution by category
* Bar Chart: Movies and TV Shows by Release Year
* Map Visualization: Content by Country
* Donut Chart: Titles by Rating
* Image & Title Section: Netflix Logo and Dashboard Header

**Page 2 – Category & Duration Insights**

* Stacked Bar Chart: Top 5 Movie Categories vs TV Show Categories
* Histogram: Typical Runtime Distribution for Movies
* Column Chart: Most Common Number of Seasons in TV Shows
* Tree Map: Category Popularity by Count
* Slicer: Filter by Type (Movie/TV Show)
* Slicer: Filter by Country
* KPI Cards: Longest Movie Duration, Average TV Show Seasons

Page 1:
<img width="1029" height="588" alt="image" src="https://github.com/user-attachments/assets/c6a39407-adbf-4f47-a599-f102159d83d5" />

Page 2:
<img width="1024" height="573" alt="image" src="https://github.com/user-attachments/assets/9b8ca195-46aa-45ad-875b-53f2653bee4e" />

