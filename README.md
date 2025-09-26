# Space Missions Analytics Dashboard

# About This Project

**Space Missions Analytics Dashboard** is a professional, portfolio-ready Power BI project that analyzes fictional global space missions.  

It provides insights into:  
- Mission success and failure rates  
- Rocket costs and investment efficiency  
- Temporal and company-wise trends  
- Rocket performance by status (Active/Inactive)

This project demonstrates **advanced DAX calculations, KPI design, and interactive dashboards**, simulating real-world aerospace decision-making for investment and risk management.

## How This Helps Stakeholders
- Quickly identifies **best-performing companies** for investment  
- Highlights **risk areas and costly failures**  
- Provides **cost-efficiency insights** to guide future funding  
- Supports **data-driven decision-making** for international space projects

<img width="1412" height="794" alt="image" src="https://github.com/user-attachments/assets/c6a71a5a-0393-46a6-a91b-8070bd5a20ea" />
  
## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Dashboard Layout & Visuals](#dashboard-layout--visuals)
  - [KPI Cards](#kpi-cards)
  - [Filter Visuals](#filter-visuals)
  - [Line Chart](#line-chart)
  - [Column Chart](#column-chart)
  - [Stacked Bar Chart](#stacked-bar-chart)
  - [Clustered Column Chart](#clustered-column-chart)
- [Analysis & Insights](#analysis--insights)
- [Recommendations](#recommendations)
- [Technical Skills Demonstrated](#technical-skills-demonstrated)
- [Portfolio Notes](#portfolio-notes)
---

## Project Overview
This project is a **data-driven analysis of global space missions** conducted by private and government space companies.  
The purpose of this dashboard is to **analyze mission performance, costs, and rocket efficiency** to support strategic investment decisions for stakeholders like the **International Space Consortium (ISC)**.

The dashboard provides **interactive visualizations** to explore:  
- Mission success and failure rates  
- Rocket costs and investment efficiency  
- Temporal and company-wise trends  
- Rocket performance by status (Active/Inactive)

This project is created using **Power BI** and is intended as a **portfolio-ready professional case study** demonstrating end-to-end data analysis skills.

---

## Dataset
The dataset consists of fictional space mission records with the following fields:

| Field | Description |
|-------|------------|
| Company | Company responsible for the space mission |
| Location | Location of the launch |
| Date | Date of the launch |
| Time | Time of the launch (UTC) |
| Rocket | Name of the rocket used for the mission |
| Mission | Name of the space mission |
| RocketStatus | Status of the rocket as of August 2022 (Active or Inactive) |
| Price | Cost of the rocket in millions of USD |
| MissionStatus | Status of the mission (Success, Failure, Partial Failure, Prelaunch Failure) |

---

## Dashboard Layout & Visuals

### KPI Cards
| KPI Name | Description |
|----------|------------|
| **Total Companies** | Total number of unique companies in the dataset |
| **Total Missions** | Total number of missions conducted |
| **Successful Mission %** | Percentage of missions with MissionStatus = Success |
| **Failed Mission %** | Percentage of missions with MissionStatus = Failure, Partial Failure, or Prelaunch Failure |
| **Total Investment ($M)** | Sum of all rocket costs (in millions of USD) |
| **Average Rocket Price ($M)** | Average rocket cost per launch |

### Filter Visuals
- Filters allow interactive exploration of:  
  - **Company**  
  - **MissionStatus**  
  - **RocketStatus**  

### Line Chart
- **Title:** *“Number of Missions by Year”*  
- Shows the **temporal trend of launches**, enabling stakeholders to see growth in space activities over time.  

### Column Chart
- **Title:** *“Number of Missions by Company”*  
- Displays the **mission count for each company**, helping identify the most active space companies.  

### Stacked Bar Chart
- **Title:** *“Mission Count by Company and Rocket Status”*  
- Shows **Active vs Inactive rockets for each company**, providing insights into the operational health of rocket programs.  

### Clustered Column Chart
- **Title:** *“Cost per Successful vs Failed Mission by Company ($M)”*  
- Compares **Cost per Success** and **Cost per Failure**, enabling evaluation of efficiency and financial risk per company.  

---

## Analysis & Insights

### Mission Performance
- **AeroX** has the **highest success rate (92%)** with a majority of rockets active.  
- **StarNova** shows a **higher failure percentage (~35%)**, indicating operational and reliability risks.  
- Launches from **Cape Canaveral** have historically higher success rates, suggesting favorable infrastructure and conditions.  

### Rocket Economics
- Average rocket cost across all companies: ~$85M.  
- **AeroX rockets** are slightly more expensive (~$100M) but deliver **higher reliability**, reducing financial risk.  
- **LunarTech rockets** are cheaper (~$50M) but have lower success rates (~65%), increasing potential cost per failure.  

### Cost Efficiency
- **Cost per Successful Mission** highlights which companies deliver maximum value per investment.  
- **Cost per Failed Mission** identifies companies with expensive failures, supporting risk assessment for investors.  

### Temporal Trends
- Total missions **increased steadily from 2010 to 2022**, with a peak in 2020.  
- **June–August** appears to be the busiest launch period globally.  

---

## Recommendations
1. **Invest in AeroX** – high reliability, moderate cost per success, and most missions completed.  
2. **Caution with StarNova** – high failure rates and expensive failures indicate risk.  
3. **Monitor LunarTech** – lower-cost rockets may be attractive but have a higher failure impact.  
4. **Prioritize Launch Locations with Historical Success** – e.g., Cape Canaveral.  
5. **Focus Funding on Active Rocket Programs** – data shows higher success rates for active rockets.  

---

## Technical Skills Demonstrated
- Data cleaning, transformation, and filtering using **Power Query**  
- Creating **calculated measures** for Success %, Failure %, Cost per Success/Failure  
- Advanced **DAX calculations** for financial KPIs  
- Building **interactive visuals**: KPI cards, line charts, column charts, stacked bar charts  
- Dashboard **design and layout** for executive-level insights  
- Professional data storytelling for **decision-making in aerospace investments**  

---

## Portfolio Notes
- This project is designed to **showcase Power BI expertise** for personal portfolio or resume inclusion.  
- All KPIs, charts, and insights are **actionable and business-relevant**.  
- Dataset is **fictional**, but analysis simulates **real-world aerospace decision-making scenarios**.  

---

