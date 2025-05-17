# B2B Data Validation and Categorization System

## 📦 Project Overview:

In B2B procurement processes, ticket categorization and data integrity are crucial for maintaining workflow efficiency. This project focuses on building a data validation and categorization system using **Python, Power BI, and SQL**, aimed at identifying misclassified RFQs, tracking ticket reassignments, and highlighting missing data points.

---

## 🛠️ Tech Stack:

* Python (Data Extraction and Validation)
* SQL (Data Analysis)
* Power BI (Data Visualization)
* Excel (Data Preprocessing)

---

## ✅ Key Features:

1. **Data Extraction and Preprocessing:** Extracts ticket data and flags missing fields (`Location Remark`, `Possible Reason`).
2. **Data Categorization:** Categorizes tickets as RFQ, PO, or Other based on keyword mapping.
3. **Data Validation:** Flags reassigned tickets and highlights data inconsistencies.
4. **Data Visualization:** Power BI dashboard visualizing ticket flow, reassignment patterns, and data quality insights.

---

## 📊 Dashboard Overview:

* **KPI Cards:** Ticket count, reassignments, missing data points.
* **Bar Charts:** Reassignments by category and branch.
* **Pie Chart:** Assignee changes and categorization distribution.
---

## 🚀 How to Run:

1. **Clone the repository:**

```bash
  git clone https://github.com/ayushidadhich/B2B-RFQ-Data-Validation.git
```

2. **Install dependencies:**

```bash
  pip install pandas openpyxl
```

3. **Run the Python script:**

```bash
  python scripts/data_validation.py
```

4. **Open Power BI Dashboard:**

* Import `processed_data.csv`
* Connect visuals and apply DAX measures.

---

## 📁 Project Structure:

```
/B2B-RFQ-Data-Validation/
│── /data/
│   └── sample_data.xlsx
│── /scripts/
│   └── data_validation.py
│── /dashboard/
│   └── power_bi_dashboard.pbix
│── README.md
│── LICENSE
```

---

## 📍 Future Enhancements:

* Integrate automated data refresh for real-time monitoring.
* Implement NLP-based text classification for better categorization.
* Develop error alerts for missing or misclassified data.

---

## 📞 Contact:

Ayushi Dadhich
[LinkedIn](https://www.linkedin.com/in/ayushidadhich)
