# HR Analytics Dashboard: Employee Attrition Analysis

![HR_dashboard](https://github.com/user-attachments/assets/fca37282-6f55-4f3e-a10b-77eaf9cfc8a7)

*Power BI Dashboard Screenshot*

## 📌 Overview
An interactive dashboard analyzing key factors behind employee attrition (e.g., job role, salary, experience). Built in **Power BI** and **Tableau** for comparative analysis.

## 🛠️ Tools & Techniques
- **Tools:** Power BI, Tableau  
- **Data Cleaning:** Removed duplicates, handled NULLs, standardized values.  
- **Features:**  
  - Calculated fields (Attrition Rate, Years of Experience).  
  - Interactive filters (Department slicer) and parameters (Top-N attrition by Job Role).  
  - 5 visualizations: Bar charts, pie charts, area charts.  

## 📊 Key Insights
1. **Attrition Peaks:** 59 employees left at 2 years of tenure.  
2. **Salary Trend:** 163 attrition cases in the <5K salary slab.  
3. **Job Roles:** Sales Reps had the highest attrition rate (23.9%).  

## 🔍 Comparative Analysis (Power BI vs. Tableau)
- **Power BI:** Default cross-filtering across visuals; measures require explicit DAX formulas.  
- **Tableau:** Easier dimension/measure conversion; manual filter application needed.  

## 📂 Repository Structure
HR-Analytics-Dashboard/
├── data/ # Cleaned dataset
│ └── HR_Analytics.csv
├── powerbi/
│ └── HR_Analytics_PowerBI.pbix
├── tableau/
│ └── HR_Analytics_tableau.twbx
├── docs/ # Report & screenshots
│ ├── Critical_Reflection.pdf
│ └── screenshots/
└── README.md


## 🚀 How to Use
1. Download the `.pbix` (Power BI) or `.twbx` (Tableau) file.  
2. Open in the respective tool and interact with filters/parameters.  

## 💡 Why This Project?
- Demonstrates **end-to-end data storytelling** from cleaning to visualization.  
- Highlights **tool proficiency** and **business impact** (HR retention strategies).  
