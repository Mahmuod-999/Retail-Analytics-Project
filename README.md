


#  Customer Sales Analysis & VIP Segmentation Project

## **Project Overview**

This project focuses on analyzing customer sales data to extract meaningful insights, identify VIP customers, detect outliers, and build a fully interactive Power BI dashboard.
The workflow includes **data cleaning, exploratory analysis, outlier detection, RFM segmentation, and dashboard development**.

This project demonstrates strong skills in **Python, Pandas, Data Analysis, Data Cleaning, and Power BI**.

---

## **Project Structure**

```
├── data/
│   ├── online_retail.csv
│   └── cleaned_data.xlsx
│
├── notebooks/
│   └── Python_Code.ipynb
│
├── reports/
│   └── Retail Project Report.pdf
│   └── Powerful Insights.pdf
│
├── dashboard/
│   └── Dashboard.pbix
│
└── README.md
```

---

##  **Technologies Used**

* **Python** (Pandas, NumPy)
* **Jupyter Notebook**
* **Power BI**
* **Excel / CSV**


---

##  **Data Cleaning Steps**

The dataset was cleaned using a full pipeline:

###  Remove missing values

###  Remove duplicate records

###  Fix inconsistent date formats

###  Convert numeric columns

###  Handle negative values

###  Standardize product and customer fields

###  Detect and remove outliers using:

* IQR
* Z-Score
* Business rules

---

## **Exploratory Data Analysis (EDA)**

Key insights extracted:

* Top-selling products
* Highest revenue months
* Most active customers
* Average order value
* Outlier detection summary
* Customer segmentation patterns

Graphs and visualizations were generated to support findings.

---

## **VIP Customer Segmentation**

VIP customers were identified using:

### **RFM Analysis**

* **Recency**: Last purchase date
* **Frequency**: Number of orders
* **Monetary**: Total spend

Customers were labeled into:

* VIP
* Loyal
* Regular
* Low-Value

### **Outlier-Based Spend Segmentation**

Customers with extremely high purchasing values and frequency were flagged as **VIP outliers**.

---

##  **Power BI Dashboard**

The dashboard includes:

* **Sales Overview Page**
* **Customer Analysis Page**
* **VIP Customers Page**
* **Product Performance Page**

Features:

* Filters and slicers
* KPI cards (Total Sales, Avg Order Value, Total VIPs)
* Trend charts
* Drill-down interactions

---

## **How to Run the Project**

### **1. Clone the Repository**

```bash
git clone https://github.com/yourusername/your-repo-name.git
```

### **2. Install Packages**

```bash
pip install -r requirements.txt
```

### **3. Run Notebook**

```bash
jupyter notebook notebooks/Python_Code.ipynb
```

### **4. Open Power BI Dashboard**

Open `Dashboard.pbix` in Power BI Desktop.

---

## **Version**

**v1.0.0 — Initial Release**

* Full data cleaning pipeline
* Outlier detection
* VIP segmentation
* EDA visualizations
* Power BI Dashboard
* Documentation completed

---

## **Author**

**Mahmoud**
Data Analyst | Python | Power BI | SQL|ُُ ُExcel




