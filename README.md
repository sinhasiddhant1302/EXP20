
#  **Experiment 20**

##  Aim:

To perform COVID-19 data analysis using Pandas and visualize insights from real-world dataset.

---

## Theory:

* **Pandas:** A Python library used for `data manipulation` and analysis using DataFrames.

* **read_csv():** Used to `load dataset` from a CSV file into a DataFrame.

* **head():** Displays the `first few rows` of the dataset for quick preview.

* **drop():** Removes unwanted columns or rows from the dataset.

* **axis:** Defines whether operation is applied on rows (0) or columns (1).

* **info():** `Provides summary` of dataset including data types, non-null values, and memory usage.

* **astype():** Used to `convert data type` of a column (e.g., string to datetime or integer).

* **datetime64:** A data type used for `storing date and time values` in proper format.

* **Feature Engineering:** Creating new columns from existing data to derive insights.

* **Active Cases:** Calculated as Confirmed − Recovered − Deaths to find current cases.

* **max():** Returns `maximum value` from a column (used to find latest date).

* **Filtering:** Selecting rows based on conditions using boolean indexing.

* **groupby():** Groups data based on a column and performs aggregation.

* **Aggregation:** Applying functions like `sum()`, `mean()` on grouped data.

* **sum():** Calculates `total values` for grouped data.

* **reset_index():** Converts grouped index into a normal column.

* **nunique():** Returns number of `unique values` in a column.

* **unique():** Returns unique elements present in a column.

* **iloc:** Used for `integer-based indexing` to access specific rows.

* **Sorting:** Arranging data in `ascending` or `descending` order using `sort_values()`.

* **sort_values():** Sorts dataset based on column values.

* **Boolean Indexing:** Used to filter data using conditions (e.g., country == India).

* **fillna():** `Replaces missing values` with specified value.

* **Choropleth Map:** A map visualization where regions are colored based on data values.

* **px.choropleth():** Used to create `world map` visualization using Plotly.

* **locationmode:** Defines how `location data` is interpreted (e.g., country names).

* **color_continuous_scale:** Defines `color gradient` used in map visualization.

* **range_color:** Sets range for color scaling.

* **Time Series Analysis:** Analysis of data over time using date column.

* **Date-wise Grouping:** Grouping data by date to analyze trends over time.

* **Top N Analysis:** Selecting top records (e.g., top 20 countries) based on values.

* **Data Cleaning:** Handling missing or inconsistent data for accurate analysis.

---

##  Conclusion:

This experiment helped in analyzing real-world COVID-19 data using Pandas. It improved understanding of data cleaning, grouping, filtering, and visualization techniques. It also demonstrated how to extract meaningful insights such as active cases, country-wise analysis, and time-based trends.

---
