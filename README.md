# Food Delivery Data Analysis

This project demonstrates how to combine and analyze data from multiple file formats (CSV, JSON, and SQL) to generate meaningful business insights.

---

## 📂 Files Used

- **orders.csv** – Transactional order data  
- **users.json** – User master data (city, membership type)  
- **restaurants.sql** – Restaurant master data (cuisine, rating)  
- **final_food_delivery_dataset.csv** – Final merged dataset (output)  
- **Food_Project.ipynb** – Jupyter Notebook containing all code and analysis

---

## 🔗 Data Integration

The datasets were merged using the following keys:

- `orders.user_id = users.user_id`  
- `orders.restaurant_id = restaurants.restaurant_id`  

A **LEFT JOIN** strategy was used to ensure that all order records were retained.

---

## 🛠️ Steps Performed

1. Loaded CSV data using Pandas  
2. Loaded JSON data using Pandas  
3. Loaded SQL data using SQLite  
4. Merged all datasets into a single dataset  
5. Cleaned duplicate columns  
6. Created `final_food_delivery_dataset.csv`  
7. Performed data analysis using Pandas

---

## 📊 Analysis Performed

Using the final dataset, the following insights were derived:

- City-wise revenue from Gold members  
- Cuisine-wise average order value  
- User spending behavior  
- Revenue distribution by restaurant ratings  
- Membership impact (Gold vs Regular)  
- Quarterly revenue trends

---

## 📁 Output

The final dataset generated is:

