✈️ Airlines Flights Analysis Dashboard – Power BI Project
📁 Dataset Overview
This project analyzes a Flights Booking Dataset scraped from a popular booking website. It contains structured, date-wise records of flight travel between major Indian cities.

The dataset includes key flight information such as:

Source and destination cities

Departure and arrival times (grouped by time bins)

Flight duration

Ticket class

Days left until travel

Ticket price
…and more.

🔹 Data Format: CSV
🔹 Data Type: Structured, cleaned
🔹 Analysis Tool: Power BI
🔹 Languages Used: Python (for preprocessing), DAX (Power BI measures)

🎯 Objective
To extract business insights and answer relevant questions for stakeholders in the airline and travel industry, using interactive visualizations in Power BI.

📊 Main Features/Columns
Column Name	Description
Airline	Name of the airline (6 unique airlines)
Flight	Flight code
Source City	City of departure (6 unique cities)
Departure Time	Time of departure (grouped into 6 categories)
Stops	Number of stops (Non-stop, 1 Stop, 2+ Stops)
Arrival Time	Time of arrival (grouped into 6 categories)
Destination City	City of arrival
Class	Ticket class (Economy / Business)
Duration	Flight duration in hours
Days Left	Days remaining until flight departure
Price	Ticket price (target variable)

❓ Business Questions Answered
What are the airlines in the dataset, accompanied by their frequencies?

Show bar graphs representing the Departure Time & Arrival Time.

Show bar graphs representing the Source City & Destination City.

Does price vary with different airlines?

Does ticket price change based on the departure and arrival time?

How does the price change based on Source and Destination cities?

How is the price affected when tickets are booked 1 or 2 days before departure?

How does ticket price vary between Economy and Business class?

What is the average price of a Vistara flight from Delhi to Hyderabad in Business Class?

📈 Visualizations Included
Cards: Total Flights, Unique Airlines, Cities, Avg. Ticket Price, etc.

Bar Charts: Departure Time, Arrival Time, Source City, Destination City

Donut Charts: Airline distribution, Class comparison

Scatter/Bubble Chart: Price variation across airlines

Line Chart: Price trend vs Days Left

Matrix/Table: Average prices by class, city, and airline

Filters/Slicers: Airline, Class, Source/Destination

🎨 Design Notes
Consistent color scheme inspired by airline booking platforms

Sky Blue and Navy Blue used to reflect a professional, clean aviation theme

Same categories are shown with matching colors across visuals (e.g., Airlines in bar & donut charts)

📌 Insights Highlighted
Evening flights are the most common departure category.

Price increases as the number of days left decreases.

Business class tickets are significantly more expensive than economy.

Some airlines consistently charge higher prices for the same routes.

📁 Tools Used
Power BI (visualization and DAX measures)

CSV file – as the source dataset

📬 Contact
For questions or suggestions, feel free to reach out.
