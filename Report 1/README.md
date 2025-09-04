# AI-Based Traffic Accident Hotspot Prediction

This repository contains my academic project on utilizing Artificial Intelligence and machine learning to proactively predict traffic accident hotspots. The project analyzes a dataset of 10,000 accident records to provide actionable insights for improving road safety.

### **Project Overview**

The core objective of this project is to move beyond traditional, reactive methods of identifying accident hotspots. The system applies a two-pronged machine learning approach:

1.  **Clustering for Hotspot Identification:**
    - I used **K-Means clustering** on geographical data (latitude and longitude) to identify 12 distinct high-risk zones within the Delhi-NCR region.

2.  **Classification for Severity Prediction:**
    - I developed a multi-class classification model to predict accident severity (e.g., "Casualty," "Serious Injury").
    - Models tested include **Random Forest**, **Logistic Regression**, and **XGBoost**.
    - **Random Forest** achieved the best performance with **82% accuracy**, a precision of 0.81, and a recall of 0.79.

### **Key Findings and Insights**

- **Critical Features:** Feature importance analysis revealed that **Weather Condition**, **Road Type**, and **Time of Day** are the most significant predictors of accident severity.
- **Strategic Recommendations:** The project provides strategic recommendations for city planners and traffic authorities, such as implementing dynamic speed advisories and weather-based driver alerts.

### **Search Algorithms for Proactive Response**

The project also explores the application of advanced search techniques for real-time decision-making:
- **BFS (Breadth-First Search):** For a comprehensive sweep of immediate response options when an incident is detected.
- **DFS (Depth-First Search):** To trace causal chains and identify hidden dependencies that escalate risk.
- **A* and UCS (Uniform Cost Search):** For optimal, risk-aware routing and resource allocation.

This project demonstrates my skills in machine learning model development, data analysis, and the practical application of AI to solve critical, real-world problems.
