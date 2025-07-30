# Netflix Content Analysis Dashboard  

![PowerBI](https://img.shields.io/badge/Power_BI-F2C811?logo=powerbi) ![Excel](https://img.shields.io/badge/Excel-Data_Source-217346?logo=microsoft-excel)  
![Data Source](https://img.shields.io/badge/Data-Kaggle-20BEFF?logo=kaggle)  

## 📌 Overview  
An **interactive Power BI dashboard** (connected to an Excel backend) analyzing Netflix's content library. Highlights trends in content growth, genre popularity, ratings distribution, and global production. Designed for data-driven decision-making in content strategy.  

### 🔍 Key Questions Answered  
- **Content Growth**: How has Netflix’s content (movies vs. TV shows) evolved over time?  
- **Genre & Ratings**: What are the most popular genres and content ratings?  
- **Global Production**: Where is Netflix content produced, and how is it distributed?  

---

## 🛠️ Tech Stack  
- **Primary Tool**: **Power BI** (Dashboard Visualization)  
- **Data Processing**: **Microsoft Excel** (Cleaning & Analysis)  
  - Pivot Tables (dynamic summarization)  
  - `SUMIFS`/`VLOOKUP` (data aggregation & matching)  
- **Integration**: Power BI directly connected to Excel for seamless data refreshes.  

## 📂 Data Source  
Dataset: [Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows) (Kaggle)  

---

## 📊 Dashboard Features  

### **1. Overview Dashboard** *(Power BI Visualizations)*  
- **Line Graph**: Movies vs. TV shows added over time.  
- **Bar Charts**:  
  - Top 10 genres (e.g., International Movies, Dramas).  
  - Content distribution by rating (e.g., TV-MA, PG-13).  
- **Map Visualization**: Country-wise content production (U.S. leads).  

### **2. Detailed Title Explorer** *(Excel-Powered Search)*  
- **Searchable Table**: Filter by title to view:  
  - Release year, rating, genre, description.  
  - Director, cast, and production country.  

---

## 💡 Business Insights & Impact  
✅ **Content Strategy**: Identifies whether Netflix prioritizes movies or TV shows.  
✅ **Genre Optimization**: Highlights high-demand genres for targeted production.  
✅ **Regional Focus**: Reveals top content-producing countries for localization.  
✅ **Audience Targeting**: Rating trends help tailor content for demographics.  

---

## 🚀 How to Use  
1. **Power BI Dashboard**:  
   - Open `Netflix_Dashboard.pbix` in Power BI Desktop.  
   - Ensure the connected Excel file (`Netflix_Data.xlsx`) is in the same directory.  
2. **Excel Backend**:  
   - Raw data and calculations are maintained in Excel for transparency.  
   - Use slicers in Power BI for dynamic filtering (year, rating, country).  

---
✨ **Key Integration Note**:  
- Power BI pulls live data from Excel, ensuring the dashboard updates when the Excel file is modified.  

---
*For feedback or questions, reach out via [GitHub Issues](https://github.com/yourusername/your-repo/issues).*  
