# Cab Booking Performance Analysis Dashboard | Power BI

## Project Overview

This project analyzes cab/ride-hailing booking data to uncover key operational and business insights using Microsoft Power BI.

The dashboard provides analysis of:

- Booking trends and volume
- Trip completion & cancellation rates
- Revenue and fare insights
- Driver performance
- Customer demographics & ride behavior
- Peak hours and demand patterns
- Vehicle type and city-wise analysis
- Payment mode insights

The goal of this project is to transform raw cab booking data into meaningful business insights through data modeling, DAX calculations, and interactive visualizations.

---

## Dashboard Preview

### Home
![Home](HOME.png)

### Dashboard Overview
![Dashboard](DASHBOARD.png)

### Booking Trends
![Booking Trends](BOOKING%20TRENDS.png)

### Driver Performance
![Driver Performance](DRIVER%20PERFORMANCE.png)

### Revenue Analysis
![Revenue Analysis](REVENUE%20ANALYSIS.png)

### Data Model View
![Model View](MODEL%20VIEW.png)

> **Note:** Replace the placeholder image files above with your actual dashboard screenshots (same filenames, or update the links to match your file names).

---

## Tools & Technologies

- Power BI
- DAX
- Power Query
- Data Modeling
- Excel / CSV Dataset

---

## Data Model

The project follows a **Star Schema** approach.

**Dimension Tables**
- Calendar Table
- Customer Details
- Driver Details
- Vehicle Details
- City / Location Details

**Fact Tables**
- Bookings
- Trips
- Transactions / Payments

---

## Dashboard Features

### 1. Booking Overview
KPIs:
- Total Bookings
- Total Trips Completed
- Cancellation Rate
- Total Revenue
- Average Fare per Trip
- Total Active Drivers

### 2. Booking & Trip Analysis
Insights:
- Booking trends over time (daily/monthly/yearly)
- Peak hour and peak day demand
- Trip status breakdown (completed, cancelled, no-show)
- City-wise and vehicle-type-wise booking distribution

### 3. Driver & Revenue Analysis
Insights:
- Driver-wise trip and revenue performance
- Payment mode distribution (cash, card, wallet, UPI)
- Average trip distance and duration
- Revenue contribution by city/vehicle type

---

## Key Business Insights

- Identified peak booking hours and high-demand locations
- Analyzed cancellation rates and their impact on revenue
- Evaluated driver performance and trip efficiency
- Compared revenue distribution across cities and vehicle types
- Improved operational decision-making through visualization
- Analyzed payment mode preferences among customers

---

## ⚙️ Requirements

To open and explore this project, you need the following tools:

| Tool | Purpose |
|------|---------|
| Microsoft Power BI Desktop | Open, view, and interact with the dashboard |
| Power Query (included in Power BI) | Data cleaning and transformation |
| DAX Engine (included in Power BI) | Execute calculated measures |
| Excel / CSV Reader | View and edit source datasets (optional) |

---

## ▶️ How to Run the Project

### Step 1: Install Power BI Desktop
Download and install Microsoft Power BI Desktop.
Official download: https://powerbi.microsoft.com/desktop/

### Step 2: Clone the Repository
```bash
git clone https://github.com/<your-username>/cab-booking-performance-analysis-power-bi.git
```
Or download the repository as a ZIP file and extract it.

### Step 3: Open the Power BI File
Open `Cab Booking Performance Analysis Dashboard.pbix` using Power BI Desktop.

### Step 4: Update Data Source Paths (if required)
If Power BI cannot locate the dataset:
1. Open Power BI Desktop
2. Go to **Home → Transform Data → Data Source Settings**
3. Select the dataset location
4. Update the file path
5. Click **Apply Changes**

### Step 5: Refresh the Data
After connecting the dataset:
**Home → Refresh**

Power BI will load the latest data and update all visuals.

---

## 📂 Project Structure

```
cab-booking-performance-analysis-power-bi/
│
├── Cab Booking Performance Analysis Dashboard.pbix
├── Cab_Booking_Data (fact&dimension).xlsx
├── HOME.png
├── DASHBOARD.png
├── BOOKING TRENDS.png
├── DRIVER PERFORMANCE.png
├── REVENUE ANALYSIS.png
├── MODEL VIEW.png
└── Readme.md
```

---

## 🔧 System Requirements

**Recommended:**
- Windows 10/11
- Microsoft Power BI Desktop (latest version)
- Minimum 4GB RAM (8GB+ recommended)
- Internet connection (for downloading Power BI Desktop)

> **Note:** Power BI Desktop is currently available for Windows only. Mac users can view reports through Power BI Service or use a Windows virtual machine.

---

## ✅ Expected Output

After opening the `Cab Booking Performance Analysis Dashboard.pbix` file, you will be able to:

- View interactive dashboards
- Apply filters and slicers
- Analyze booking and trip trends
- Explore driver and revenue performance
- Review calculated KPIs and insights
