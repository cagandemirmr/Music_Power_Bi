# 🎵 Music Power BI Analysis Project

## 📌 Project Overview
This project involves recreating a previous SQL-based music data analysis using Power BI. By setting up relationships between tables, writing DAX functions, and creating interactive visuals, I optimized the data model and reporting. The main goal of this project was to answer critical business questions and gain insights using key performance indicators (KPIs).

---

## 🛠️ Data Preparation and Cleaning

### 1. Data Checking
- Imported the dataset into Power Query Editor.
- **Checked for missing values**, **duplicates**, and **errors** to ensure data integrity.
- Cleaned and transformed the data before loading it into the Power BI model.

![Data Cleaning](https://github.com/user-attachments/assets/c96fab15-96f0-4309-834d-51c67fa0e46e)

### 2. Data Modeling
- Set up a **star schema** to optimize the data structure and relationships.
- Fact and dimension tables were separated to enhance performance and streamline reporting.

![Star Schema](https://github.com/user-attachments/assets/969640f1-74cd-46fb-8995-7ceb91db437c)

---

## 📊 KPI Analysis and Dashboard

### Key Performance Indicators (KPIs)
1. **Total Revenue**: Sum of all sales across all channels.
2. **Total Number of Purchases**: Total count of all transactions.
3. **Total Customer Count**: Number of unique customers.

These metrics are essential for evaluating business performance.

![KPIs](https://github.com/user-attachments/assets/2f6341f4-07c7-44c3-af41-7eb4a4e922d1)

- **Revenue** data was extracted from the `invoice` table, while **purchase counts** and **customer IDs** were pulled from `invoice_line`.
- Using the `RELATED` DAX function, I connected the `Genre` table to `invoice_line` to analyze revenue by genre.

---

## 📈 Visualizations and Insights

### 1. Top 5 Countries by Total Revenue
- Created a **Tree Map** to visualize the top-performing countries by revenue.

![Tree Map](https://github.com/user-attachments/assets/8b7abc1f-d2ca-4340-aa27-6aa0c8dcb97a)

### 2. Distribution of Music Genres
- Used a **Donut Chart** to showcase the distribution of genres.

![Donut Chart](https://github.com/user-attachments/assets/be66a8f9-7b76-497f-a0e3-a93f8dae4478)

### 3. Interactive Slicers
- Added slicers to filter data by **Genre** (vertical) and **Date** (dropdown) for enhanced interactivity.

![Slicers](https://github.com/user-attachments/assets/33132b8b-5af9-4347-a0c4-071737b910c6)

### 4. Revenue by Genre and City
- Created a **Line and Stacked Column Chart** to compare average and total revenue by city.

![Stacked Chart](https://github.com/user-attachments/assets/1d603ae5-ff7f-4a24-a2a5-0ea3e4f483b4)

### 5. Yearly and Monthly Revenue Trends
- Used a **Waterfall Chart** to observe changes in revenue over the years.

![Waterfall Chart](https://github.com/user-attachments/assets/6534cc8d-7a82-4234-8206-8e443f715f01)

### 6. Top Customers by Purchases
- Created a **Table** to display the top customers by total purchases, using an N filter.

![Top Customers Table](https://github.com/user-attachments/assets/808512e5-c605-414a-9119-1af8727d01cb)

---

## 📋 Pop-up Window Feature
- Added a **pop-up window** for additional insights without cluttering the main dashboard.
- Created shapes with 50-60% transparency for a background effect.
- Used bookmarks to control the appearance of the pop-up.

![Pop-up Feature](https://github.com/user-attachments/assets/4b0859b9-c072-48cb-bafa-809a9fe75498)

### Additional Insights
1. **Top Rock Artists by Album Count**
   - Pie chart showing rock artists who produced the most albums.

   ![Pie Chart](https://github.com/user-attachments/assets/f4f40635-d409-4f2e-9ea3-d59c7b2786c5)

2. **Top 10 Rock Fans by Purchases**
   - Table showing the top 10 rock fans based on the amount of shopping.

   ![Top Fans Table](https://github.com/user-attachments/assets/47282edd-1cd9-4bcf-9ee2-61113f203d32)

### Pop-up Interaction
- **Blank button** used to close the pop-up window.
- Grouped all elements to appear as a single pop-up and used bookmarks to toggle visibility.
- Created a button on the main dashboard to trigger the pop-up display.

![Pop-up Button](https://github.com/user-attachments/assets/3fb7de2b-211b-44e4-920b-e48a36f3c741)

---

## 📌 Conclusion
This Power BI project allowed me to explore interactive reporting and data visualization techniques effectively. By leveraging DAX functions, slicers, and dynamic visuals, I was able to provide actionable insights for music sales analysis. The pop-up window feature also enhanced the interactivity of the dashboard, making it user-friendly and engaging.

Feel free to explore the dashboard and provide feedback!

---

## 🛠️ Tools and Technologies
- **Power BI**: Data visualization and reporting.
- **Power Query**: Data cleaning and transformation.
- **DAX (Data Analysis Expressions)**: Calculations and metrics.
- **GitHub**: Project repository and version control.


