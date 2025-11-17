📊 Insurance Risk & Claims Analysis – Power BI Dashboard

A complete end-to-end Power BI analytics project designed to help an insurance company understand its policyholder profile, claim behaviour, and risk patterns using interactive dashboards and dynamic measures.

🚀 Project Overview

Insurance companies handle massive amounts of customer and claims data, which are often scattered across multiple systems.
This project focuses on building a centralized, dynamic, and interactive Power BI dashboard that helps stakeholders analyze:

Policy distribution

Claim trends

Demographic segmentation

Car details & risk factors

Customer behaviour patterns

The dashboard transforms raw data into actionable insights for better decision-making, risk assessment, and policy optimization.

🏢 Business Requirement

The insurance company needs a unified reporting system to monitor KPIs and visualize risk-related attributes.
The goal is to help decision-makers:

Track financial impact

Identify high-risk customer groups

Improve policy targeting

Analyze claim frequency & severity

Understand demographic & vehicle-based patterns

📌 Key Business KPIs

The following KPIs were developed using DAX:

KPI	Description
Total Policies	Measures total active policy count.
Total Claim Amount	Shows the overall claim payout.
Claim Frequency	Number of claims submitted.
Average Claim Amount	Average payout per claim.
Gender-wise Total Policies	Helps understand customer distribution by gender.
📊 Visualization Requirements & Insights

The dashboard contains several visuals built around two dynamic measures:
🔹 Total Policies and 🔹 Total Claim Amount

1️⃣ Car Use – Donut Chart

Shows how vehicles are used (Personal / Commercial).

Helps identify which segment generates more policies or claims.

2️⃣ Car Make – Bar Chart

Compares claim amounts and policy counts across car brands.

Useful for detecting high-risk brands.

3️⃣ Coverage Zone – Donut Chart

Breaks down claims & policies by regional zone.

Ideal for regional risk analysis.

4️⃣ Age Group – Frequency Chart / Histogram

Shows distribution of policyholders by age.

Highlights segments with higher claim frequency.

5️⃣ Car Year – Area Chart

Visualizes how vehicle manufacturing year impacts risk.

Older cars typically show higher claim severity.

6️⃣ Kids Driving – Ribbon Chart

Compares households with young drivers vs. no young drivers.

Helps understand additional risk exposure.

7️⃣ Education Level – Pie Chart

Shows how education influences insurance adoption & claims.

Supports customer segmentation.

8️⃣ Education + Marital Status – Matrix Heat Grid

Displays combined effect of education and marital status.

Identifies high-value or high-risk demographic groups.

🧩 Data Model (Star Schema)

The data model was designed using a Star Schema for optimized DAX performance and faster report refresh.

      Fact_Claims
            |
    ----------------
    |       |      |
Dim_Policy Dim_Customer Dim_Car


Fact Table: Claims, Claim Amount, Policy ID

Dimension Tables: Customer, Car, Policy Details

This model ensures:
✔️ Clean relationships
✔️ Fast filtering
✔️ Efficient measure calculations

🛠️ Tools & Technologies Used

Power BI Desktop

Power Query (ETL)

Power BI DAX

Star Schema Data Modeling

Data Cleaning & Transformation

Excel / CSV (Source Files)

📥 Project Files Included

.pbix – Power BI Dashboard

/Data – Raw data sources (CSV/Excel)

README.md – Documentation

Screenshots folder (optional)

🖼️ Dashboard Sneak Peek

(Add your dashboard images here)

Example:

/images/dashboard_home.png  
/images/kpi_overview.png  
/images/claims_charts.png  

📈 Key Insights From the Dashboard

Certain car makes show consistently higher claim amounts.

Commercial-use cars have higher claim frequency compared to personal-use cars.

Policyholders aged 25–35 form the majority customer base.

Specific zones contribute to a higher percentage of total claim amount.

Households with young drivers show increased risk indicators.

Education and marital status combinations strongly affect policy purchase behavior.

▶️ How to Use This Report

Download the .pbix file from the repository.

Open in Power BI Desktop.

Load the dataset or replace it with your own source.

Explore interactive visuals using slicers and filters.

Analyze trends across demographics, vehicle attributes, and claim patterns.

📌 Future Enhancements

Integration with real-time data sources (SQL / API).

Predictive model for claim severity using Python.

Monthly and Yearly trend forecasting.

Policy renewal recommendation engine.
