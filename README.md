# **Warehouse Optimization for an Agricultural Non-Profit**
This repository contains the **data science workflow** for optimizing warehouse locations for an agricultural non-profit. Using **Python, R, SQL, clustering, geospatial analysis, and data visualization**, this project identifies the best warehouse locations based on farm density, supplier networks, and accessibility.

---

## **📌 Project Overview**
Agricultural supply chains require efficient warehouse placement to minimize transportation costs and maximize accessibility. This project evaluates potential locations using a **data-driven approach**, analyzing supplier distributions, farm density, and marginalized group representation.

### **Key Components**
- **Demand Clustering**: Used **K-Means clustering** to segment farm locations based on supplier density.
- **Distance-Based Optimization**: Computed **geodesic distances** to identify optimal warehouse coverage.
- **Scoring Algorithm**: Designed a **weighted ranking system** to evaluate warehouse placement.
- **Interactive Dashboard**: Created **a Tableau dashboard** to visualize the results dynamically.

---

## **🔧 Technologies Used**
- **Languages**: Python, R, SQL
- **Libraries**: pandas, geopandas, scikit-learn, folium, geopy, seaborn, matplotlib
- **Database**: PostgreSQL
- **Visualization**: Tableau, Excel

---

## **📁 Repository Structure & Files**

📂 Warehouse-Optimization-Data-Science
│── 📜 README.md                   # Project Overview & Instructions
│── 📂 data                         # Raw and cleaned datasets
│   │── USDA_NASS_data.csv          # Raw USDA NASS data for farm statistics
│   │── Map_2024_with_County.csv    # Supplier and buyer locations for warehouse evaluation
│── 📂 notebooks                    # Jupyter Notebooks for data analysis
│   │── Demand_Clustering.ipynb     # Clustering and demand analysis for warehouse selection
│── 📂 reports                      # Project reports and presentations
│   │── TGA_Analysis_EDA.xlsx       # Primary exploratory data analysis (EDA) in Excel
│   │── The Good Acre Presentation.pdf # Final presentation summarizing key insights
│── 📂 dashboard                    # Tableau dashboard and visualization files
│   │── TGA_Dashboard.twbx          # Interactive Tableau dashboard for decision-making

---

## **🚀 Step-by-Step Guide**
### **1. Data Collection & Exploration**
- **USDA_NASS_data.csv** → Contains farm density, acreage, and marginalized group representation.
- **Map_2024_with_County.csv** → Supplier and buyer locations for warehouse evaluation.
- **TGA_Analysis_EDA.xlsx** → Primary exploratory data analysis (EDA) done in Excel.

### **2. Data Processing & Clustering**
- **Demand_Clustering.ipynb** → Jupyter notebook where:
  - **K-Means Clustering** was applied to segment farm locations.
  - **Geospatial analysis** identified the most accessible warehouse locations.
  - **Distance calculations** were used to optimize supplier routing.

### **3. Scoring & Warehouse Selection**
- Integrated clustering results with a **weighted scoring system**.
- Evaluated warehouse locations based on **demand, equity, and efficiency metrics**.

### **4. Dashboard & Visualization**
- **TGA_Dashboard.twbx** → Interactive Tableau dashboard:
  - Displays warehouse rankings.
  - Provides dynamic filters for decision-making.
  - Visualizes demand clusters and accessibility.

### **5. Presentation & Insights**
- **The Good Acre Presentation.pdf** → Final presentation summarizing key findings and recommendations.

---

## **📊 Findings & Insights**

### **1. Optimized Warehouse Location**
- Steele County emerged as the **top-ranked location**, scoring **1.39** based on farm density, marginalized farmer support, and supplier connectivity.
- **Kandiyohi County** was the next best option, offering **balanced growth potential and localized market connectivity**.
- **Otter Tail County** showed **promising market connectivity** but had fewer emerging farms.
- **Olmsted County** was deprioritized due to **high overlap with Steele and lower farm density**.
- **St. Louis County** ranked lowest due to **low agricultural activity and infrastructure saturation**.

### **2. Data-Driven Scoring & Ranking**
- Developed a **flexible scoring system** incorporating **farm density, acreage, marginalized groups, suppliers, and buyers**.
- Allowed **dynamic weight adjustments** in the **interactive dashboard** to refine decision-making.
- Ensured the **model aligned with the organization's mission**, prioritizing emerging farms and equitable access.

### **3. Coverage & Accessibility Analysis**
- Calculated **warehouse service areas** using supplier travel distances.
- Identified **existing warehouses that overlap** with new locations to avoid redundancy.
- Provided **county-wide supply chain insights**, ensuring maximum impact.

### **4. Predictive Insights for Future Planning**
- Used **projections from 2017 and 2022 Census data** to model **post-pandemic agricultural recovery**.
- Forecasted **future farm activity trends**, enabling long-term strategic planning.

### **5. Business & Community Impact**
- **Reduced transportation inefficiencies** by optimizing warehouse placements.
- **Improved accessibility** for marginalized farmers, ensuring equitable distribution of resources.
- Delivered **actionable recommendations** in an easy-to-use **Tableau dashboard**.

This analysis provided a **data-driven framework** for **scalable warehouse expansion** while ensuring equity and operational efficiency.



