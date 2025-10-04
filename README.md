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

**Page 1**

* KPI Cards: Total Titles, Total Movies, Total TV Shows, Total Genres
* Bar Chart: Rating Distribution Across Content
* Area Chart: Content Released Over Years
* Donut Chart: Movies vs Tv Show
* Slider: Filter by Type (Movie/TV Show) 


**Page 2**
* KPI Cards: Earlier Content Added, Latest Content Added
* Tree Map: Content distribution by category(Top 5)
* Bar Chart: Rating Distribution for Movies Vs Shows
* Histogram: Typical Runtime Distribution for Movies
* Column Chart: Most Common Number of Seasons in TV Shows
* Slider: Filter by Release Year

Page 1:
<img width="1029" height="588" alt="image" src="https://github.com/user-attachments/assets/c6a39407-adbf-4f47-a599-f102159d83d5" />

Page 2:
<img width="1015" height="572" alt="image" src="https://github.com/user-attachments/assets/43d43af7-5b51-4c6d-9e1b-21dd2a824095" />

📂 Data Files
* Netflix_Data_Analysis.pbix → Power BI project file containing all visualizations, models, and dashboard pages.
* original_netflix_dataset.csv → Original Dataset imported from kaggle.
* netflix_transformed.csv → Cleaned and transformed dataset after data preparation in Power Query.
* category_mapping.csv → Separate mapping table showing each show’s association with multiple categories.
* README.md → Project overview, key learnings, and documentation of transformations and visuals.
