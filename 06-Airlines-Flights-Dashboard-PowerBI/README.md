# ✈️ Airlines Flights Analysis Dashboard – Power BI Project

An interactive Power BI dashboard that analyzes flight booking data between major Indian cities to uncover pricing patterns and business insights for the airline and travel industry.

---

## 📁 Dataset Overview

This project analyzes a **Flights Booking Dataset** scraped from a popular booking website. It contains structured, date-wise records of flight travel between major Indian cities.

The dataset includes key flight information such as:

- Source and destination cities
- Departure and arrival times (grouped into time bins)
- Flight duration
- Ticket class
- Days left until travel
- Ticket price
- ...and more

| Property | Details |
|----------|---------|
| 🔹 **Data Format** | CSV |
| 🔹 **Data Type** | Structured, cleaned |
| 🔹 **Analysis Tool** | Power BI |
| 🔹 **Languages Used** | Python (preprocessing), DAX (Power BI measures) |

---

## 🎯 Objective

To extract business insights and answer relevant questions for stakeholders in the airline and travel industry, using interactive visualizations in Power BI.

---

## 📊 Main Features / Columns

| Column Name | Description |
|-------------|-------------|
| **Airline** | Name of the airline (6 unique airlines) |
| **Flight** | Flight code |
| **Source City** | City of departure (6 unique cities) |
| **Departure Time** | Time of departure (grouped into 6 categories) |
| **Stops** | Number of stops (Non-stop, 1 Stop, 2+ Stops) |
| **Arrival Time** | Time of arrival (grouped into 6 categories) |
| **Destination City** | City of arrival |
| **Class** | Ticket class (Economy / Business) |
| **Duration** | Flight duration in hours |
| **Days Left** | Days remaining until flight departure |
| **Price** | Ticket price (target variable) |

---

## ❓ Business Questions Answered

1. What are the airlines in the dataset, and how frequent is each?
2. Show bar graphs representing Departure Time and Arrival Time.
3. Show bar graphs representing Source City and Destination City.
4. Does price vary with different airlines?
5. Does ticket price change based on departure and arrival time?
6. How does price change based on Source and Destination cities?
7. How is the price affected when tickets are booked 1 or 2 days before departure?
8. How does ticket price vary between Economy and Business class?
9. What is the average price of a Vistara flight from Delhi to Hyderabad in Business Class?

---

## 📈 Visualizations Included

- **Cards:** Total Flights, Unique Airlines, Cities, Avg. Ticket Price, etc.
- **Bar Charts:** Departure Time, Arrival Time, Source City, Destination City
- **Donut Charts:** Airline distribution, Class comparison
- **Scatter / Bubble Chart:** Price variation across airlines
- **Line Chart:** Price trend vs. Days Left
- **Matrix / Table:** Average prices by class, city, and airline
- **Filters / Slicers:** Airline, Class, Source / Destination

---

## 🎨 Design Notes

- Consistent color scheme inspired by airline booking platforms
- Sky Blue and Navy Blue used to reflect a professional, clean aviation theme
- Same categories shown with matching colors across visuals (e.g., airlines in bar and donut charts)

---

## 📌 Insights Highlighted

- ✅ Evening flights are the most common departure category.
- ✅ Price increases as the number of days left decreases.
- ✅ Business class tickets are significantly more expensive than economy.
- ✅ Some airlines consistently charge higher prices for the same routes.

---

## 🛠️ Tools Used

- **Power BI** – visualization and DAX measures
- **CSV file** – source dataset
- **Python** – data preprocessing

---

## 📬 Contact

For questions or suggestions, feel free to reach out.

---

## 📄 License

This project is released under the MIT License — feel free to use it for
learning or as a portfolio reference.

---

## 👨‍💻 Author

**Sara Ibrahim**  
*Data Scientist | Machine Learning / AI Engineer*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/sara-ibrahim-omran)  
[![Email](https://img.shields.io/badge/Email-Contact%20Me-red?style=flat&logo=gmail)](mailto:Saraomran433@gmail.com)

### 🌟 Let's Connect!

I'm passionate about solving real-world problems with data, machine learning, and AI. Feel free to reach out for:

- 💼 Job opportunities and collaborations
- 📚 Technical discussions and knowledge sharing
- 🚀 Project ideas and innovative solutions

**⭐ If you find this project helpful, please give the repo a star!**
