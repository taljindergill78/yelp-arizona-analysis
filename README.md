# Arizona Business and User Insights from Yelp Data

This project analyzes the Yelp dataset for the state of Arizona to extract insights about restaurant businesses and user behavior. Using Apache Spark and PySpark for distributed data processing, the project demonstrates how big data tools can be used to uncover patterns in customer reviews, business performance, and user engagement.

> 🧠 **Note**: Though conducted under the ASU CSE 511 course, this was a fully individual project built from scratch to explore large-scale data processing and analytics.

---

## 📁 Project Structure
```yelp-arizona-analysis/
├── data/ # Reference to external Yelp dataset
│ └── README.md # Contains link to dataset source
├── notebooks/ # Jupyter Notebooks with code
│ ├── business_level_analysis.ipynb
│ └── user_level_analysis.ipynb
├── reports/ # Final PDF reports
│ ├── business_level_report.pdf
│ └── user_level_report.pdf
├── .gitignore
└── README.md
```

---

## 🗂 Dataset

[Yelp Open Dataset](https://www.yelp.com/dataset)  
Used 5 JSON files: `business`, `review`, `user`, `tip`, and `checkin`. Data was filtered to include only businesses in Arizona.

---

## 🧾 Business Level Analysis

**Objective**: Analyze Arizona restaurants by category, location, pricing, service patterns, and elite reviews.  
**Techniques Used**:
- Spark SQL joins on JSON datasets
- Filtering by city, price range, and operational schedule
- Analysis of geographic and seasonal review trends
- Elite reviewer impact and cuisine popularity

📄 [Read Report](reports/business_level_report.pdf)

---

## 👥 User Level Analysis

**Objective**: Examine Yelp user behavior, contribution levels, sentiment patterns, and geographic influence.

**Techniques Used**:
- Engagement index based on fans, reviews, and votes
- Comparison of elite vs regular users
- Seasonal activity trends and review variability
- Review quality scoring and consistency evaluation

📄 [Read Report](reports/user_level_report.pdf)

---

## 🛠 Tools Used

- Apache Spark & Spark SQL
- PySpark
- Jupyter Notebook
- JSON to Parquet conversion
- Ubuntu Virtual Machine (local Hadoop+Spark environment)

---

## 📌 Author

**Taljinder Singh**  
Graduate Student, MS in Data Science  
Arizona State University  
[LinkedIn](https://www.linkedin.com/in/taljindersingh)

---

## 📜 License

This project is for academic and learning purposes.