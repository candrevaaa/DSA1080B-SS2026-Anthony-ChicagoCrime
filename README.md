# Strategic Resource Optimization: Chicago Crime Analysis (2026)


## 1. Project Overview
This project analyzes crime data from the City of Chicago for the early months of 2026. The primary objective is **Resource Optimization**: identifying spatial and temporal patterns to propose a distribution model that maximizes the "positive effect" of existing public safety assets. I move beyond simple frequency counts to focus on **Arrest Efficiency** across different districts and timeframes.

## 2. Dataset Description
* **Source:** [City of Chicago Data Portal - Crimes 2026](https://data.cityofchicago.org/)
* **Observations:** 36,000+ rows
* **Variables:**
| Column Name | Description |
| :--- | :--- |
| **ID** | Unique identifier for the record. |
| **Case Number** | The Chicago Police Department RD Number. |
| **Date** | Date and time when the incident occurred. |
| **Primary Type** | The main category of the crime (e.g., Theft, Battery). |
| **Description** | A subcategory of the primary crime type. |
| **Location Description** | The type of location where the incident occurred (e.g., Street, Residence). |
| **Arrest** | Boolean indicating if an arrest was made. |
| **Domestic** | Boolean indicating if the incident was domestic-related. |
| **District** | The police district where the incident occurred. 

## 3. Key Findings
* **The Efficiency Gap:** We identified that high-volume districts often reach a "resource saturation point," where arrest rates drop significantly compared to lower-volume districts.
* **Temporal Peaks:** Crime frequency peaks sharply between **8:00 PM and 10:00 PM**, highlighting a critical window for dynamic staff reallocation.
* **Specialization Paradox:** While specialized crimes (Narcotics) have high arrest rates, property crimes (Theft) have a major clearance deficit, identifying a need for investigative refocusing.

## 4. Recommendations
* **Dynamic Power Shifts:** Implement flexible staffing models that intensify resources during identified peak temporal windows. 
* **KPI-Driven Reallocation:** Utilize the District Efficiency Ranking to rebalance mobile support units from high-efficiency areas to resource-saturated districts. 
* **Environmental Specialization:** Prioritize deterrence-based resources for street segments and investigative response teams for residential segments. 

## 5. Tools Used
* **Language:** Python 3.x
* **Libraries:** Pandas (Data Cleaning), Matplotlib & Seaborn (Visualization), NumPy (Calculations).
* **Environment:** VS Code, Jupyter Notebooks.
* **Version Control:** GitHub.

## 6. Academic Integrity and AI Declaration
* I hereby declare that this project is my original work. All data sources have been cited appropriately.
* **AI Disclosure:** Large Language Models (Gemini) were utilized for guidance on Python syntax, report structuring, and README formatting. All analytical conclusions and strategic recommendations were derived from my own interpretation of the dataset.

## 7. Project Contributer
* Anthony Ogolla - 676933