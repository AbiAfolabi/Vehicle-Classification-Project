# Vehicle Transmission Classifier – Go Auto Project

**Introduction**

This project aims to develop a machine learning model that classifies vehicles as having either an automatic or manual transmission, using recent vehicle listing data from Go Auto dealerships in Edmonton. By analyzing features such as year, make, model, mileage, and price, the model supports more efficient inventory categorization and targeted marketing efforts. The project also includes exploratory data analysis, preprocessing, and data visualization using Power BI to uncover business insights and guide strategic decisions.


**Project Overview**

This project is developed in collaboration with Go Auto, using a dataset compiled by their Business Intelligence Team with data sourced via APIs from the Canadian Black Book (CBB). The dataset includes detailed vehicle listings (both active and sold) across multiple dealerships in Edmonton over the last 30 days. The main objective is to apply Exploratory Data Analysis (EDA) and develop a binary classification model to identify the transmission type (automatic or manual) of each vehicle. This insight can help streamline inventory classification and support targeted marketing strategies tailored to buyer preferences. The final project includes interactive visualizations built in Microsoft Power BI to help stakeholders at Go Auto derive actionable business insights.

**Objective**

The goal of this project is to:
- Build a classification model to predict whether a vehicle has an automatic or manual transmission
- Use vehicle features such as year, make, model, mileage, and price
- Address challenges related to imbalanced datasets
- Provide business insights and recommendations for Go Auto based on the data analysis and model results

**Problem Statement**

Vehicle Transmission Identifier (Classifier):
Create a machine learning model that can accurately classify a vehicle's transmission type as automatic or manual using available listing data.

**Dataset Description**

The dataset contains recent vehicle listings from Go Auto dealerships, with features including:
- Year – Model year of the vehicle
- Make – Manufacturer (e.g., Toyota, Ford)
- Model – Specific model name
- Mileage – Distance driven
- Price – Listed price
- Dealership Information – Location and listing details
- Transmission – Target variable (automatic/manual)
- Additional contextual features may be explored and engineered as needed during analysis.

**Project Phases**

Phase 1: Dataset Exploration & Preprocessing

- Checked for missing or inconsistent values
- Explored feature distributions and relationships
- Performed encoding, normalization, and other preprocessing tasks
- Addressed class imbalance using techniques such as oversampling or class weighting

Phase 2: Model Development

- Built baseline models (e.g., Logistic Regression) to classify transmission type
- Evaluated performance using classification metrics: Accuracy, Precision, Recall, F1 Score
- Analyzed feature importance and model interpretability


Phase 3: Visualization & Business Reporting

- Developed dashboards using Power BI to communicate:
- Model results and performance
- Data insights and vehicle trends
- Recommendations tailored for business decision-makers

**Model Evaluation**

Models were evaluated using:
- Accuracy: Overall correctness
- F1 Score: Balance between precision and recall (especially important for imbalanced data)
- Confusion Matrix: Visual representation of classification performance

**Key Insights & Recommendations**

- Inventory Classification: Automated identification of transmission types reduces manual entry errors.
- Targeted Marketing: Dealerships can promote manual or automatic vehicles to the right customer segments.
- Pricing Strategy: Pricing trends can be adjusted based on transmission type preferences and market demand.

**Deliverables**

- Cleaned and preprocessed dataset
- Machine learning classification model
- Power BI dashboard visualizations
- Final report with business recommendations and model analysis

**Tools & Technologies**

- Python (Pandas, Scikit-learn, NumPy, Matplotlib)
- Power BI (for interactive data visualizations)
- Google Collab Notebooks
- Git/GitHub (for version control and collaboration)

**Learning Outcomes**

- Project Development: Build a portfolio-ready project with a complete workflow from concept to delivery.
- Teamwork & Strategy: Practice real-world collaboration and cross-functional planning.
- Communication Skills: Engage with stakeholders, present insights clearly, and network with industry professionals.

**Contributors**

Abi Afolabi - aafolabi@norquest.ca

Abiola Bakare - abakare69@norquest.ca

Chioma Ulom - culom@norquest.ca

Gift Ajayi - gajayi@norquest.ca

Moyosore Akinola - makinola@norquest.ca
