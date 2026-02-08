# Uber Ride Data Analysis | Power BI Dashboard

## Project Overview
This project analyzes Uber ride booking data to understand booking behavior, revenue patterns, and operational efficiency.

The analysis initially started as a general exploratory study. During exploration, a critical issue was identified — a **high ride cancellation rate (~38%)**.  
Based on this insight, the project was extended into a focused **cancellation analysis and optimization study**.

Both phases are implemented within a **single Power BI file**, logically divided into:
- **DB1 – Exploratory Analysis**
- **DB2 – Cancellation Analysis & Optimization**

---

## Business Problem
A significant percentage of ride bookings were being cancelled, leading to revenue loss and poor customer experience.

The objective of this project is to:
- Identify cancellation patterns
- Understand root causes
- Propose data-driven solutions to reduce cancellations

---

## Dashboard Structure

### DB1 – Exploratory Analysis
**Purpose:** Understand overall business performance and uncover hidden issues.

Includes:
- Booking and revenue KPIs
- Booking status distribution
- Time-based trends (monthly, weekday vs weekend, peak vs non-peak)
- Fare and payment analysis
- Vehicle type and location performance

**Key Discovery:** ~38% of total bookings were cancelled

---

### DB2 – Cancellation Analysis & Optimization
**Purpose:** Deep-dive into the cancellation problem identified in DB1.

Includes:
- Driver vs customer cancellation analysis
- Cancellation reasons
- Time-slot and location-based cancellation patterns
- Vehicle-type impact on cancellations
- Identification of cancellation hotspots
- Solution and optimization insights

---

## Dashboard Screenshots

### Home Page
<img src="Dashboard/1.Home Page.png" width="900"/>

---

### DB1 – Exploratory Analysis

#### Overview
<img src="Dashboard/2.Overview.png" width="900"/>

#### Time-Based Analysis
<img src="Dashboard/3.Time.png" width="900"/>

#### Fare Analysis
<img src="Dashboard/4.Fare.png" width="900"/>

---

### DB2 – Cancellation Analysis & Optimization

#### Cancellation Overview
<img src="Dashboard/5.Cancellation Overview.png" width="900"/>

#### Root Cause Analysis
<img src="Dashboard/6.Root Cause Analysis.png" width="900"/>

#### Solution & Optimization Insights
<img src="Dashboard/7.Solution & Optimization Insights.png" width="900"/>

---

## Key Insights
- Approximately **38% of total ride bookings are cancelled**
- Driver-side cancellations contribute more than customer cancellations
- Peak hours and high-demand locations show higher cancellation density
- Economy vehicle types dominate both bookings and cancellations
- Medium-distance rides contribute the most to overall revenue

---

## Recommendations
- Introduce zone- and time-based driver incentive programs
- Improve driver allocation during peak demand hours
- Enhance ETA accuracy and in-app communication
- Optimize surge pricing logic using demand signals
- Reduce dependency on cash payments

---

## Tools & Technologies
- Power BI
- DAX
- Excel / CSV
- Data Modeling
- Time Intelligence

---

## Project Files & Access
- Dashboard screenshots are available in the `Dashboard/` folder
- Dataset access link is provided in the repository
- Due to GitHub file size limitations, the Power BI (.pbix) file is hosted externally

---

## Power BI File
**Download (.pbix):**  
https://drive.google.com/file/d/1SkltWbqFdFlyX1vbhicQKG0436kPB9m_/view?usp=drive_link

https://app.powerbi.com/links/c_8cmFMKdE?ctid=61e6000a-7d75-4846-9c6b-60c345837481&pbi_source=linkShare

---

## Author
**Sumeet Patra**  
Data Analyst | Power BI | SQL | Python
