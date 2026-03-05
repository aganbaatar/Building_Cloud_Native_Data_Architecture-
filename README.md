## AWS Cloud-Native Bankruptcy Prediction Pipeline
This project prototypes a cloud-native analytics architecture for MSBA Financial Group to centralize financial data and support predictive analysis. Data from multiple sources—company financial statements, calculated accounting ratios, and bankruptcy records—are ingested into a data lake, transformed through ETL/ELT processes, and stored in a data warehouse to create a centralized “single source of truth.” Exploratory Data Analysis (EDA) is then performed, and a machine learning model is built to predict the likelihood of companies filing for bankruptcy in the next fiscal year. 

The project uses AWS cloud tools for data storage, transformation, and analytics, along with Python-based data analysis and machine learning libraries to perform EDA and build the bankruptcy prediction model.

### Tools Used

- Amazon S3 – Served as the data lake to store raw financial, ratio, and bankruptcy datasets from multiple sources.

- AWS Glue / ETL Processes – Used to clean, transform, and integrate the datasets into a structured format suitable for analysis.

- Amazon Redshift – Functioned as the centralized data warehouse, consolidating financial statements, ratios, and bankruptcy data into a single source of truth for analysis.

- Amazon SageMaker – Used to perform Exploratory Data Analysis (EDA) and develop a machine learning model predicting the likelihood of corporate bankruptcy.

- Python (Pandas, Scikit-learn, Matplotlib/Seaborn) – Used for data preparation, analysis, visualization, and building the predictive model.

Project Presentation Video: https://www.loom.com/share/c87e2b5006fd4b36a1e85a8909714d1b 
