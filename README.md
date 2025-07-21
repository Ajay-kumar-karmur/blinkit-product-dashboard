# 🛍️ BlinkIt Product Analytics Dashboard

An interactive dashboard application built using **Python** and **Streamlit** to analyze and visualize BlinkIt product data. This project allows users to upload a CSV file, filter and explore product insights by categories, brands, pricing, stock status, and more — all through a clean and intuitive interface.

---

## 📁 Project Structure

```
├── main.py                 # Streamlit app logic
├── blinkit_sample_data.csv # Sample data (120+ records)
├── requirements.txt        # Python dependencies
└── README.md               # Project overview (this file)
```

---

## 🧰 Tools & Technologies

- **Python 3**
- **Pandas** for data manipulation
- **Streamlit** for dashboard UI
- **Altair/Plotly** for data visualization

---

## 📊 Features

- **CSV Upload**: Supports user-uploaded data for dynamic analysis  
- **Category Filters**: Filter data by primary (`l1_category`) and secondary (`l2_category`) categories  
- **Brand Analysis**: View product counts and pricing trends by brand  
- **Discount Insights**: Compare MRP vs Selling Price and calculate discounts  
- **Stock Status**: Analyze which products are in stock or out of stock  
- **Interactive Visuals**: Graphs and charts for brand distribution, stock levels, and pricing  
- **Data Search**: Search by product name (variant)  
- **Export**: Optionally save filtered results (code included)

---

## 📂 Sample Data Format

The app expects a CSV file with the following columns:

| Column Name      | Description                          |
|------------------|--------------------------------------|
| `date`           | Date of data collection              |
| `l1_category`    | Primary category                     |
| `l2_category`    | Secondary category                   |
| `variant_name`   | Product name                         |
| `selling_price`  | Current selling price                |
| `mrp`            | Maximum retail price                 |
| `in_stock`       | Stock availability (True/False)      |
| `brand`          | Product brand                        |
| `inventory`      | Inventory count                      |
| `is_sponsored`   | Sponsored status (True/False)        |

A valid sample file `blinkit_sample_data.csv` with 120+ records is included for testing and demonstration.

---

## 🧪 How to Run on Replit

1. Open the project link.
2. Click the green **Run** button.
3. Upload the provided CSV file when prompted.
4. Explore the dashboard in the right pane.

---

## 📌 Notes for Reviewers

- Project is developed and tested entirely within Replit.
- All required packages are listed in `requirements.txt`.
- Designed to work without any API keys or internet-based dependencies.
- Clean, modular code for easy understanding and extension.

---

## 👨‍💻 Developed By

**Ajay Kumar Karmur**  
🎓 B.E. in Computer Science & Engineering  
📧 ajaykumarkarmur5760@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/ajay-kumar-karmur)

---

## 📅 Submission

**Project Completed:** July 21, 2025  
**Platform:** Replit  
**Hosted/Shared via:** Replit project link

---

## 📃 License

Free to use for educational and academic review purposes.
