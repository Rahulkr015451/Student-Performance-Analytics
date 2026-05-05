# Student Performance Analytics: Attendance vs. Academic Success

An end-to-end data analytics project exploring the impact of classroom attendance and internal assessments on final examination outcomes. This project leverages **Python** for statistical modeling and **Power BI** for interactive business intelligence.

## 📌 Project Overview
Using a dataset of **2,000 student records**, this project quantifies how much "showing up" actually matters. By applying **Linear Regression** and **Correlation Analysis**, we move past anecdotal evidence to provide a data-driven threshold for academic success.

## 📊 Key Findings
*   **Strong Correlation:** A Pearson Correlation coefficient of **0.73** indicates a high positive relationship between attendance and final marks.
*   **Predictive Power:** The model achieves an **R-Squared ($R^2$) of 0.5266**, meaning attendance alone explains approximately **53%** of the variance in final scores.
*   **The "Attendance Gap":** There is a **21-mark difference** between students in the "Critical" tier (<75% attendance) and the "Excellent" tier (>85% attendance).
*   **The Predictive Model:** 
    $$Score = (1.06 \times Attendance) - 25.19$$
    *For every 1% increase in attendance, a student's final score is predicted to rise by 1.06 marks.*

## 🛠️ Tech Stack
*   **Data Analysis:** Python (Pandas, NumPy)
*   **Visualizations:** Matplotlib, Seaborn
*   **Machine Learning:** Scikit-Learn (Linear Regression)
*   **Business Intelligence:** Power BI Desktop (DAX, Interactive Dashboards)
*   **Environment:** Google Colab

## 📂 Project Structure
*   `Final_Marks_Data.csv`: The raw dataset containing 2,000 records.
*   `Student_Performance_Analysis.ipynb`: The Google Colab notebook containing data cleaning, EDA, and regression modeling.
*   `Performance_Dashboard.pbix`: The interactive Power BI dashboard featuring KPI cards and a "What-If" prediction slider.
*   

## 🚀 How to Run
1.  **Python Analysis:** Open the `.ipynb` file in Google Colab and upload the `Final_Marks_Data.csv` to run the statistical pipeline.
2.  **Dashboard:** Open `Performance_Dashboard.pbix` in Power BI Desktop to interact with the performance tiers and predictive slider.

## 💡 Conclusion & Strategy
The data confirms that attendance is a functional driver of grades. Students dropping below **75% attendance** are statistically "At-Risk," averaging scores near the failing threshold. This project provides a framework for educational institutions to trigger early interventions based on real-time attendance data.

---
**Developed by Rahul K R  
