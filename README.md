# Athletic Performance Analysis - University Rugby Team (PowerBI)

This project presents a comprehensive **Athletic Performance Analysis** of a university rugby team using **PowerBI**.  
The dashboard transforms raw player performance data into actionable insights that help coaches and sports analysts evaluate **power output**, **relative strength**, **z-scores**, **percentiles**, and **position-based trends**.

---

## **Project Overview**

Using a dataset containing performance outputs from rugby players across different positions, this analysis focuses on:

- Evaluating **Peak Power Output (PWR)**  
- Assessing **Relative Power (W/kg)**
- Highlighting the **Change in Relative power from the last test** 
- Identifying top performers and players needing support  
- Highlighting positional performance differences  
- Exploring performance trends over time for the last 5 seasons
- Providing coaches with data-driven insights for training decisions
- Providing a weekly summary report for the coaches

---

## **Dataset Description**

The dataset contains the following variables:

| Column        | Description |
|---------------|-------------|
| **PLAYER**    | Name or ID of the athlete |
| **DATE**      | Date of performance test |
| **POSITION**  | Playing position in the rugby team |
| **PWR (W)**  | Peak power output in watts |
| **MASS (kg)** | Body mass in kilograms |
| **RELATIVE (W/kg)** | Power output relative to body mass |
| **Z-SCORE**   | Standardised performance score based on team distribution |
| **PERCENTILE** | Percentile ranking of the athlete compared to the team |

---

## **Tools & Technologies**

- **PowerBI** – Preprocessing, Data modelling, Dashboards & visualization  
- **Excel / CSV** – Data storage 
- **DAX** – Custom measures and calculated fields  

---

## **Key Dashboards & Insights**

The PowerBI dashboard consists of:

### 1. Player Performance Overview  
- Individual metrics  
- Position-based comparison   

### 2. Z-Score Explorer  
- Identifies above/below average performers  
- Highlights outliers  

### 3. Relative Power Breakdown  
- Compares fair metrics across body weights  
- Useful for strength & conditioning teams  

### 4. Time-Series Trend Analysis  
- Shows how player's performance evolves across testing dates  
- Highlights improvements & regressions  

Screenshots are available in the folder:  
`/powerbi/screenshots/`

---

## 📂 **Repository Structure**

```
athletic-performance-analysis/
│
├── data/
│   ├── raw/
│
├── report/
│   ├── Performance Report.pbix
│
└── README.md
```

---

## **How to Use This Project**

1. Download the **PBIX file** from `/powerbi/`  
   *(or use the Google Drive link if the file exceeds GitHub size limit)*  
2. Open in **PowerBI Desktop**  
3. Explore dashboards: player comparisons, positional metrics, z-score insights  
4. Modify data or visuals as required for research or coaching needs  

---

## **Future Improvements**

- Integrate machine learning to predict performance changes  
- Add injury history and training load data  
- Automate data ingestion using Python  
- Build a web dashboard version using Streamlit/Plotly  

---

## **About the Author**

Master’s student in **Data Science & AI**, with skills in:

- Python  
- SQL  
- R  
- PowerBI  
- Statistical analysis  
- Sports performance analytics  

Happy to collaborate on similar analytics or performance projects.

---

## Contact

If you'd like to explore or collaborate:  
**Email:** ajayadarshms@gmail.com  
**LinkedIn:** www.linkedin.com/in/ajay-adarsh-s


---

If you find this project useful, feel free to star the repository!
