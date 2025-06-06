# Superstore-Sales Data Analysis

## Project Overview
This project aims to analyze Superstore sales data to uncover business insights using Python and visualize them through a professional Power BI dashboard. This project demonstrates data cleaning, preprocessing, exploratory data analysis, and visual storytelling.

##  Dataset Information

- **Source:** Sample Superstore Dataset (CSV format).
- **Rows:** ~10,000 order records.
- **Columns include:**
  - Order Date, Sales, Profit, Quantity.
  - Region, Segment, Category, Sub-Category.
  - City, State, Ship Mode, Customer ID.

---

##  Data Cleaning Process

### 1. Initial Data Exploration:
- Checked dataset shape and structure using `.info()` and `.head()`.
- Identified columns useful for analysis.

### 2. Handling Missing Values:
- Checked for missing values using `.isnull().sum()`.
- No critical missing values were found in the key columns.

### 3. Duplicate Check:
- Verified duplicates using `.duplicated().sum()`.
- No duplicate rows found.

### 4. Data Type Conversion:
- Converted `Order Date` to datetime format.
- Verified numerical columns like `Sales`, `Profit` were floats.

---

##  Exploratory Data Analysis (EDA)

### 🔹 Univariate Analysis:
- Sales distribution using descriptive stats and bar plots.
- Frequency of Ship Mode, Segment, Region, and Category.
- Identified top-selling Sub-Categories and standard ship mode was dominating.

### 🔹 Bivariate Analysis:
- Sales by Region, Segment, and Ship Mode.
- Sales by Category and Sub-Category.
- State and City wise sales performance.

---

##  Power BI Dashboard

The dashboard provides a high-level visual summary of sales data.

###  Key Visuals:
- Total and Average Sales KPIs
- Sales by Region, Segment, Category, and Ship Mode
- Map showing State-wise sales
- Detailed view of sales across sub-categories.

###  Highlights:
- **Consumer Segment** leads in sales
- **Phones** and **Chairs** are top-selling sub-categories
- **California** and **New York** are revenue leaders
- **Standard Class** is the most used shipping method

>  *Dashboard preview image available in `assets/dashboard_screenshot.png`*

---

##  How to Run the Project

### 🔹 Google Colab:
1. Open `superstore_sales_analysis.ipynb` in Colab
2. Upload `superstore_dataset.csv`
3. Run all cells to see data cleaning and EDA outputs

### 🔹 Power BI:
1. Open `Superstore_Sales_Dashboard.pbix` in Power BI Desktop
2. Interact with the visuals and explore the insights

---

##  Tools and Technologies

 - **Python (Colab)** : Data Cleaning & EDA            
 - **Pandas & Seaborn** : Data Analysis & Visualization 
 - **Matplotlib**   : Static Plotting                 
 - **Power BI**     : Interactive Dashboard           

---

##  Conclusion

This project demonstrates how data from a retail superstore can be cleaned, analyzed, and visualized to uncover valuable business insights. Combining Python for analysis and Power BI for dashboards creates a powerful end-to-end data solution suitable for real-world business applications.



