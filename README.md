# Palmora Group HR Analysis (Power BI Capstone)
This project delivers a comprehensive HR analytics dashboard for Palmora Group, built using Power BI. The analysis explores gender distribution, salary structure, performance ratings, and regulatory compliance. It also includes bonus allocation based on employee performance and salary band distribution by region. The dashboard supports data-driven decisions in HR management, with interactive filters and visuals for deeper insight.

---

## Palmora Group HR Analysis
This project presents a comprehensive HR analysis for the Palmora Group, using **Power BI** for interactive dashboards and data-driven insights. It highlights key HR metrics such as gender distribution, salary structure, regulatory compliance, and total compensation.

---

## Tools & Technologies Used
   - **Power BI**
   - **Power Query** (Data Cleaning & Transformation)
   - **DAX** (Data Modeling & Calculations)
   - Data Visualization
    
---

### Dashboard Preview

![Image](https://github.com/kimizzy001/DSA-Project-Documentation/blob/main/palmora%20e.jpg)

The dashboard answers **critical HR questions** and supports **data-driven decision-making**. Below are the key analyses performed: 

---

### Key Insights & Case Questions Addressed:
1. **Gender Distribution Analysis**
   - Visualized organization-wide gender breakdown
   - Filtered by Region and Department

2. **Employee Rating by Gender**
   - Compared performance ratings across male, female, and unspecified genders
      
3. **Company Salary Structure**
   - Analyzed salary distribution across genders
   - Identified presence of gender pay gaps
   - Highlighted specific regions and departments needing attention
       
4. **Regulatory Salary Compliance Check**
   - Verified adherence to the $90,000 minimum wage requirement
   - Identified 654 employees earning below this threshold
   - Displayed pay distribution in $10,000 bands by region

 
5. **Bonus & Total Compensation Calculation**
   - Calculated individual bonuses
   - Computed total pay = Salary + Bonus
   - Analyzed total compensation by region and company-wide

---

#### Key Insights
1. **Gender Distribution by Region & Department**
      - Overall gender split:
         - Female: 49.15%
         - Male: 44.12%
         - Unspecified: 6.73%
      - Gender representation is fairly balanced.
      - Gender distribution was further broken down across regions (Lagos, Abuja, Kaduna) and departments, enabling HR to monitor diversity more accurately.

 2. **Performance Ratings by Gender**    
       - Ratings were originally in text format (e.g., Very Good, Average, etc.) and were converted to numeric scores.
       - Analysis showed that Male and Female employees have similar average performance ratings, with no significant disparity.
       - Most employees fall into the “Good” or “Very Good” categories.

 3. **Company Salary Structure & Gender Pay Gap**
       - A gender pay gap was identified:
       - Male employees tend to receive higher average salaries across most regions and departments.
       - Breakdown by department and location revealed that some departments (e.g., Legal, Marketing) and regions (e.g., Abuja) exhibit wider gender-based salary differences.
       - These areas should be prioritized by management for a pay equity audit.

  4. **Minimum Salary Compliance**
       - The new regulation mandates a minimum annual salary of $90,000 for all employees.
       - The analysis found 654 employees earn below this threshold, indicating non-compliance.
       - Employees were grouped into salary bands (e.g., $90K–$100K, $100K–$110K, etc.) and analyzed by region.
       - Kaduna has the highest share of underpaid employees and total salary spend, making it the key region for compliance intervention.

  5. **Bonus Allocation Based on Ratings**
       - Bonus amounts were calculated using a separate dataset containing rules based on performance ratings.
       - A total of $2.20M was allocated as bonuses company-wide.
       - Each employee’s total compensation (salary + bonus) was calculated.
       - Summary of bonus allocation:
       - Kaduna received the highest share of total bonus payout.
       - Bonus distribution aligns with performance rating scores.

---

### Recommendations
   - Address salary non-compliance immediately, especially in Kaduna.
   - Investigate and resolve gender-based pay gaps, focusing on specific departments and regions.
   - Improve data completeness by minimizing “Unspecified” gender entries.
   - Continue using performance-based bonus structures, but ensure fairness and transparency.

---

### Tools Used
   - Power BI Desktop
   - DAX for calculated measures (e.g., average salary, bonus logic)
   - Tooltip customization
   - Slicers and filters for user interactivity

---

### Final Notes

This project fulfills the capstone requirement for the Data Science Accelerator (DSA) program.  
It demonstrates not only technical proficiency in Power BI and DAX, but also the ability to extract meaningful business insights and communicate them through clear, interactive visuals.  
The focus on gender distribution, compensation equity, and regulatory compliance highlights a real-world application of data-driven HR strategy.



