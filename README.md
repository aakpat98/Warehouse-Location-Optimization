# **Warehouse Optimization for an Agricultural Non-Profit**
This repository contains the **data science pipeline** for optimizing warehouse locations based on farm density, supplier networks, and accessibility. The project leverages **Python, R, SQL, clustering, geospatial analysis**, and machine learning techniques to derive actionable insights.

## **📌 Project Overview**
Agricultural supply chains require efficient warehouse placement to reduce transportation costs and improve equity for farmers. This project identifies optimal locations for a non-profit agricultural organization by:
- Analyzing **USDA NASS data**, supplier-buyer distributions, and census statistics.
- Computing **geodesic distances** between stakeholders and warehouses.
- Applying **K-Means clustering** to segment geographic regions.
- Designing a **weighted scoring algorithm** to rank potential locations.
- Developing **interactive Tableau dashboards** for decision-making.

## **🔧 Technologies Used**
- **Languages**: Python, R, SQL
- **Libraries**: pandas, geopandas, scikit-learn, folium, geopy, seaborn, matplotlib
- **Database**: PostgreSQL
- **Visualization**: Tableau

## **🛠️ Project Workflow**
1. **Data Collection & Cleaning**
   - Loaded structured and geospatial data.
   - Handled missing values and standardized formats.
   - Stored cleaned datasets in PostgreSQL.

2. **Exploratory Data Analysis (EDA)**
   - Visualized farm density and supplier distributions.
   - Computed summary statistics.

3. **Distance-Based Analysis**
   - Used `geopy.distance` to calculate warehouse proximity.
   - Evaluated supplier and buyer coverage per warehouse.

4. **Clustering & Machine Learning**
   - Applied **K-Means Clustering** to segment farm locations.
   - Integrated **existing warehouse constraints** into analysis.

5. **Scoring & Optimization**
   - Developed a multi-weight scoring system for ranking warehouse locations.
   - Normalized scoring metrics for comparability.

6. **Results & Visualization**
   - Created **interactive Tableau dashboards**.
   - Generated final warehouse recommendations.

## **📊 Key Findings**
- Identified the **top-ranked warehouse location** based on multi-factor analysis.
- Recommended **secondary locations** for scalability.
- Optimized supplier routing to minimize redundancy.
