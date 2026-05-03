# Bonus Prediction Dashboard

A React-based dashboard for bonus prediction and allocation.  
It supports CSV and Excel uploads, parses and visualizes data with **Recharts**, and enables clean data export.  
Built with **Recharts, PapaParse, XLSX, and Lucide**, this project demonstrates expertise in **front-end development, data parsing, and interactive visualization**.
---
## Problem
Enterprise bonus allocation processes are often manually computed using spreadsheets, leading to inefficiencies, inconsistent calculations, and limited data-driven insight.
---

## Solution
- Built a client-side analytics system to process CSV/Excel sales data
- Implemented data ingestion and normalization for heterogeneous transactional records
- Designed a feature extraction pipeline to structure business-relevant insights
- Developed rule-based logic for bonus prediction
- Created interactive visualizations for data exploration
- Enabled export functionality for processed results

---

## Tech Stack
- React 19
- Recharts (data visualization)
- PapaParse (CSV parsing)
- SheetJS (Excel processing)
- Lucide React (UI icons)
- JavaScript (feature engineering & rule-based modeling)
- CSS Grid + Custom Design System

---

## Key Features

- Supports CSV and Excel file ingestion
- Automatic schema normalization for inconsistent datasets
- Feature engineering for 20+ business metrics per customer
- Rule-based bonus prediction model
- Real-time interactive dashboard (KPI + charts)
- Budget reallocation with proportional scaling
- Exportable structured results (CSV download)

---

## System Flow

The system follows a client-side data processing pipeline:

**Data Flow:**
File Upload (CSV / Excel)  
→ Data Parsing (PapaParse / SheetJS)  
→ Data Normalization (schema alignment & type cleaning)  
→ Feature Engineering (20+ business metrics per customer)  
→ Rule-based Scoring (bonus prediction logic)  
→ Data Visualization (Recharts dashboard)  
→ Export (CSV download with processed results)

---
## Impact

- Eliminates manual spreadsheet-based bonus calculation workflows
- Enables automated processing of 10,000+ transactional records on the client side
- Generates 20+ structured business features per customer in real time
- Improves transparency of bonus allocation through interactive visualization
- Reduces data preparation and analysis time from manual processing to near real-time workflow
---

##  Project Results
### 1. Dashboard Development
- **Input & Data Merge**  
  Input the merged master table and annual sales data to generate the dashboard and default bonus amount.  
  ![Input & Data Merge](project-results/01_Dashboard_Input_MergedSalesData.png)

- **Annual Overview & Bonus Budget**  
  The dashboard provides an annual overview, allowing users to set the total bonus budget for the year.  
  ![Annual Overview & Bonus Budget](project-results/02_Dashboard_AnnualOverview_BonusBudget.png)

- **Dealer Bonus Management**  
  Users can view, edit, and export detailed bonus allocations for each dealer.  
  ![Dealer Bonus Management](project-results/03_Dashboard_DealerBonus_Edit_Export.png)

### 2. Reflection & Future Outlook
- **Short-term**: Interface optimization of the dashboard  
- **Mid-term**: One-click merge for three key tables  
- **Long-term**: Data quality improvement  
  ![Reflection & Future Outlook](project-results/04_FutureOutlook.png)

---
