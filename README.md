# 🚕 OLA RIDE BOOKING & BUSINESS ANALYTICS DASHBOARD

> **End-to-end data analytics project using MySQL, Excel, and Power BI to analyze ride bookings, revenue, cancellations, vehicle performance, and customer experience.**

---

## 📌 PROJECT OVERVIEW

This project analyzes **40K+ OLA ride-booking records** to identify trends and business insights across booking performance, vehicle types, revenue, cancellations, ride distance, and customer/driver ratings.

The project follows an end-to-end analytics workflow:

**MySQL → SQL Analysis → Excel Data Cleaning → Power BI Data Visualization → Business Insights**

The objective was to transform raw ride-booking data into an interactive dashboard to understand operational performance and identify areas for improvement.

---

## 📊 DASHBOARD PREVIEW

![OLA Ride Booking Dashboard](Dashboard/OLA_Dashboard.png)

---

## 🎯 BUSINESS OBJECTIVES

The analysis focuses on answering key business questions:

- What is the overall ride volume and booking performance?
- Which vehicle types generate the highest ride distance?
- What are the major reasons for customer and driver cancellations?
- Which payment methods contribute to revenue?
- Which customers have the highest booking value?
- How are customer and driver ratings distributed?
- What trends can be identified in ride distance and booking activity?
- Where are potential operational problems affecting ride performance?

---

## 📊 DATASET

The dataset contains **40K+ ride-booking records** with information related to:

- Date & Time
- Booking ID
- Booking Status
- Customer ID
- Vehicle Type
- Pickup Location
- Drop Location
- Vehicle Arrival Time
- Customer Arrival Time
- Customer Cancellations
- Driver Cancellations
- Incomplete Rides
- Booking Value
- Payment Method
- Ride Distance
- Driver Ratings
- Customer Ratings

---

## 🛠️ TOOLS & TECHNOLOGIES

| Tool | Purpose |
|---|---|
| **MySQL** | SQL queries, analysis, filtering, aggregation, and analytical views |
| **Excel** | Data cleaning, formatting, and preparation |
| **Power BI** | Interactive dashboard development and visualization |
| **DAX** | KPI calculations and business metrics |
| **Power Query** | Data transformation and preparation |

---

## 🔄 PROJECT WORKFLOW

### 1️⃣ SQL ANALYSIS — MYSQL

The raw ride-booking data was analyzed in MySQL using SQL queries and analytical views.

### Key Analysis

- Successful bookings
- Average ride distance by vehicle type
- Customer cancellation analysis
- Top 5 customers by ride count
- Driver cancellation analysis
- Maximum and minimum driver ratings
- UPI payment analysis
- Average customer rating by vehicle type
- Total successful booking value
- Incomplete rides and their reasons

A total of **10 core SQL analysis questions/views** were developed as part of the project.

---

### 2️⃣ DATA CLEANING — EXCEL

After SQL analysis, the dataset was prepared in Excel for reporting and visualization.

### Data Preparation

- Cleaned raw data
- Formatted columns and values
- Checked data consistency
- Prepared fields for analysis
- Organized categorical and numerical data
- Prepared the dataset for Power BI

---

### 3️⃣ POWER BI DASHBOARD

An interactive **5-page Power BI dashboard** was developed to convert the analyzed data into business insights.

### 📄 Dashboard Pages

#### 1. Overall

- Total booking volume
- Successful bookings
- Cancelled bookings
- Booking status breakdown
- Ride volume trends

#### 2. Vehicle Type

- Vehicle-wise ride distance
- Vehicle performance comparison
- Top vehicle types

#### 3. Revenue

- Revenue analysis
- Revenue by payment method
- Top customers by booking value
- Ride-distance distribution

#### 4. Cancellation

- Customer cancellation reasons
- Driver cancellation reasons
- Cancellation trends
- Operational problem areas

#### 5. Ratings

- Driver rating analysis
- Customer rating analysis
- Rating distribution
- Customer vs. driver rating comparison

---

## 📈 KEY PROJECT METRICS

| Metric | Result |
|---|---:|
| **Total Bookings** | **40.54K** |
| **Successful Bookings** | **25.21K** |
| **Cancelled Bookings** | **11.29K** |
| **Cancellation Rate** | **10.96%** |
| **Vehicle Types Analyzed** | **7** |
| **Average Customer Rating** | **~4.0/5** |

---

## 💡 KEY INSIGHTS

The dashboard provides visibility into:

- Overall booking and ride-volume performance
- Vehicle-type utilization and ride-distance trends
- Revenue contribution across payment methods
- Customer and driver cancellation patterns
- High-value customers
- Customer and driver rating behavior
- Ride-distance distribution
- Potential operational issues affecting successful bookings

These insights can support decisions related to **ride operations, customer experience, vehicle performance, revenue monitoring, and cancellation reduction**.

---

## 📁 PROJECT STRUCTURE

```text
OLA-Ride-Booking-Analytics/
│
├── Dataset/
│   └── OLA_Ride_Data.xlsx
│
├── SQL/
│   └── OLA_SQL_Analysis.sql
│
├── Excel/
│   └── Cleaned_OLA_Data.xlsx
│
├── PowerBI/
│   └── OLA_Ride_Analytics.pbix
│
├── Dashboard/
│   └── OLA_Dashboard.png
│
└── README.md
