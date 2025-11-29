🚀 Excited to share my latest project: **HR Analytics Dashboard built in Power BI**, powered by real workforce insights and custom **DAX calculations**!

This dashboard helps HR teams analyze:
✔ Attrition trends
✔ Active employee count
✔ Department-level risk
✔ Job satisfaction
✔ Age, gender & education patterns

📊 **Key Metrics in the Dashboard**

* Total Employees: 1470
* Active Employees: 1233
* Attrition Count: 237
* Attrition Rate: 16.1%
* Average Age: 37

💡 **DAX Measures Used**
To ensure accurate KPI calculations, I created custom DAX measures:

**Attrition Rate**

```
Attrition Rate =
    SUM('HR data'[Attrition Count]) /
    SUM('HR data'[Employee Count])
```

**Active Employees**

```
Active Employees =
    SUM('HR data'[Employee Count]) -
    SUM('HR data'[Attrition Count])
```

These measures helped transform raw HR data into clear, meaningful insights.

🧩 **What the Dashboard Reveals**

* Highest attrition is in **R&D (56%)** and **Sales (39%)**
* Job satisfaction varies across roles like Sales Executives, Research Scientists & Managers
* Most employees fall in the **25–34 age group**
* Gender distribution and education fields show impactful patterns

📈 **Why This Project Matters**
HR analytics is becoming essential for better hiring, retention, and workforce planning. With Power BI + DAX, we can help organizations make smarter, data-driven decisions.

If you're working on Power BI, HR analytics, or DAX modeling, let's connect!
#PowerBI #DAX #HRAnalytics #DataAnalytics #DashboardDesign #BusinessIntelligence #DataVisualization #DataAnalyst
