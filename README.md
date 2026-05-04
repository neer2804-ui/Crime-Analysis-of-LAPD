# 📊 LAPD Crime Intelligence Dashboard  
**Predictive and Exploratory Analysis of Urban Crime Patterns**

---

## 📌 Abstract
This project develops an interactive dashboard to analyze crime patterns using publicly available data from the Los Angeles Police Department. The objective is to uncover temporal, spatial, and categorical crime trends and support data-driven decision-making.

The system integrates data preprocessing, feature engineering, and visualization to transform raw crime records into actionable insights. The dashboard enables users to explore crime distribution across time, geography, and victim demographics, while highlighting key behavioral and environmental risk patterns.

---

## 🧠 Business Problem
Urban crime presents significant challenges for law enforcement agencies and policymakers.

**Key Question:**
> How can crime data be leveraged to identify high-risk areas, temporal patterns, and crime categories to support proactive policing and resource allocation?

---

## 📂 Dataset Overview
- **Source:** Los Angeles Police Department (Public Dataset)  
- **Records:** ~1M+ observations  

### Key Features:
- Crime Code & Description  
- Date and Time of Occurrence  
- Area Name (geographical segmentation)  
- Victim demographics (age, gender, descent)  
- Latitude and Longitude  

---

## ⚙️ Technical Approach

### 1. Data Preprocessing
- Removed redundant and high-missing-value columns  
- Standardized datetime formats  
- Handled categorical inconsistencies  
- Eliminated potential data leakage features  

---

### 2. Feature Engineering
Extracted:
- Hour of occurrence  
- Day of week  
- Month and year  

Derived Features:
- Time-of-day categories  
- Victim age groups  

Additional:
- Encoded categorical variables for analysis  

---

### 3. Dashboard Development
- Built an interactive web-based dashboard (live deployed)  

**Filters:**
- Time range  
- Crime type  
- Location  

**Visualizations:**
- Crime distribution charts  
- Temporal trend analysis  
- Geographic heatmaps  

---

## 🔍 Key Insights

### 1. Temporal Patterns
- Crime peaks during evening and late-night hours  
- Weekends show higher variability in crime types  

### 2. Spatial Distribution
- Certain areas consistently report higher crime density  
- Geographic clustering highlights localized risk zones  

### 3. Crime Categories
- Theft and assault dominate overall distribution  
- Crime types exhibit strong time dependency  

### 4. Victim Demographics
- Uneven distribution across age and demographic groups  
- Certain groups are disproportionately affected  

---

## 📈 Business Impact
This dashboard demonstrates how crime data can be transformed into actionable intelligence:

- Supports resource allocation for law enforcement  
- Enables proactive and predictive policing strategies  
- Assists in policy-making and urban planning  
- Enhances situational awareness through interactive analytics  

---

## 🛠️ Tools & Technologies
- Python (Pandas, NumPy)  
- Data Visualization Framework  
- Feature Engineering & Data Transformation  
- Web Deployment (Live Dashboard)  

---

## ⚠️ Limitations
- Missing and inconsistent records in dataset  
- No real-time data integration  
- Predictive modeling not fully integrated into dashboard  

---

## 🚀 Future Enhancements
- Integrate machine learning models for crime prediction  
- Add real-time data streaming capabilities  
- Incorporate external datasets (weather, events)  
- Improve geospatial visualization using clustering algorithms  

---

## ✅ Conclusion
This project highlights the importance of combining data engineering, analytics, and visualization to extract meaningful insights from large-scale datasets.

By transforming raw crime data into an interactive intelligence system, the dashboard demonstrates the practical application of analytics in solving real-world urban challenges.

---
<img width="1605" height="862" alt="image" src="https://github.com/user-attachments/assets/a3a4aa2f-94d9-4f39-9deb-2422e8e287b7" />

## 🔗 Live Dashboard
👉 https://lapd-crime-6xafyh77.manus.space/
