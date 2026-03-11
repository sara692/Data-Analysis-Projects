# 🌍 Global Basic Services and Geography Analysis

---

## 🌐 Background

The United Nations' first Sustainable Development Goal (SDG) is to **eradicate poverty in all its forms worldwide**.

One of the key targets under this goal, **Target 1.4**, aims to ensure that all people — particularly the poor and vulnerable — have:

- Equal rights to economic resources and basic services  
- Ownership and control over land and other forms of property  
- Inheritance, natural resources, and appropriate new technology  
- Access to financial services, including microfinance  

By 2030, progress toward this target is tracked using **Indicator 1.4.1**, which focuses on:

> _The proportion of the population living in households with access to basic services, per country._

In this project, we focus on two related SDG indicators:

- **6.1.1**: Access to safely managed drinking water services  
- **6.2.1**: Access to safely managed sanitation services  

These indicators provide critical insight into how countries are progressing toward basic service equity and SDG Target 1.4.

---

## 🧰 Tools Used

- **MySQL** (for data storage and queries)
- **Jupyter Notebook** (for analysis and documentation)
- **Python (SQLAlchemy + PyMySQL)** for database connection

---

## 📂 Project Structure

### 1. `Access_to_Basic_Services` Table
Includes:
- `Country_name`
- `Time_period`
- `Pct_managed_drinking_water_services`
- `Pct_managed_sanitation_services`
- `Est_population_in_millions`
- `Est_gdp_in_billions`
- `Pct_unemployment`

### 2. `Geographic_Location` Table
Manually structured and derived from the cleaned dataset.  
Includes:
- `Country_name` (Primary Key)
- `Sub_region`
- `Region`
- `Land_area`

---

## 🛠 Data Cleaning & Transformation

- Removed text in parentheses from `Country_name` using string functions.
- Converted column data types (e.g., population, GDP, unemployment) for consistency.
- Filled missing unemployment rates using region-based conditional logic with nested `IF` statements.
- Split dataset into logical tables (`Access_to_Basic_Services`, `Geographic_Location`) for better normalization and analysis.

---

## 📊 Sample Analysis Performed

- Calculated average and max unemployment rates per region using `OVER (PARTITION BY ...)`.
- Compared country-level data to regional aggregates.
- Created unique IDs per country-year-population combination using `CONCAT` and `SUBSTRING`.

---

## 🚀 How to Run

1. Launch your MySQL server locally.
2. Run the Jupyter Notebook:
   - Connect to the database using SQLAlchemy
   - Run each analysis step by step
3. Re-create tables using provided `CREATE TABLE` SQL code.

---

## 📌 Goals of the Project

- Practice **data analysis** using SQL and Python
- Learn about **data cleaning**, joins, and window functions
- Prepare a **professional portfolio project** for GitHub

---

## 📁 Files Included

- `un_global_services_analysis.ipynb` – main Jupyter notebook
- `README.md` – project description (this file)
- (Optional) `.sql` file with schema setup and sample data

---

## 📈 Next Steps

- Add data visualization (e.g., matplotlib or seaborn)
- Expand to include additional SDG indicators (e.g., education, health)
- Deploy as an interactive dashboard or web app (optional)

---

## 👩‍💻 Author

**Sara Ibrahim** – aspiring data analyst with a telecom engineering background  
🔗 [LinkedIn](https://www.linkedin.com/in/sara-ibrahim-omran) (update this link)
