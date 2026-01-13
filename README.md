# 📊 Energy Cost Optimization Model

## 📌 Project Objective
This project analyzes annual energy consumption to determine the most cost-effective electricity plan among three options: Fixed, Monthly, and Hourly rates. The goal is to identify savings opportunities based on real consumption patterns.

## 🧩 The Challenge: Data Transformation
The source data consisted of non-structured text strings. I developed a comprehensive **Data Cleaning Pipeline** in Excel to normalize the information:
- **String Cleansing:** Used nested functions to remove delimiters, irregular spaces, and non-numeric characters.
- **Pattern Extraction:** Isolated dates, times, and energy usage (kWh) from complex text blocks.
- **Data Standardization:** Converted raw text into a structured format ready for financial modeling.

## 🔧 Tools & Techniques
- **Advanced Excel:** (XLOOKUP, String Manipulation, Wildcard matching).
- **Financial Modeling:** Built a calculation engine to compare three different pricing structures.
- **Data Visualization:** Created an executive dashboard with KPIs and a comparative analysis chart.

## 📈 Key Insights
The analysis revealed that the **Hourly Plan** is the most profitable option for this user, offering the lowest annual cost. This is because the user's highest consumption occurs during off-peak hours when electricity is cheapest ($0.10 - $0.12/kWh).

## 🧠 Conclusion
This project demonstrates how technical data cleaning is the foundation of business intelligence. Converting "dirty" data into a structured model allows for precise operational cost optimization.
