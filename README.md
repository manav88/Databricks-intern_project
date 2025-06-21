# Databricks
This project is a comprehensive demonstration of an end-to-end data analytics pipeline built on Databricks. It was executed in the context of a simulated client project during my internship, designed solely for educational and portfolio purposes. The pipeline covers data ingestion, processing, transformation, modeling, and visualization using tools within the Databricks environment (including PySpark, Delta Lake, SQL, MLflow, and Power BI integration).


Project Workflow
	•	Data Ingestion: Raw transactional and customer data loaded from external CSV sources into Databricks File System (DBFS).
	•	Data Engineering: Cleaning, transforming, and structuring data using PySpark and SQL for downstream analytics.
	•	Delta Lake Integration: Employed Delta Lake for versioned, scalable storage and time travel capabilities.
	•	Feature Engineering: Derived features such as customer segmentation and RFM scoring for advanced insights.
	•	Exploratory Data Analysis: Performed using Spark SQL and visualized directly in Databricks notebooks.
	•	Modeling: Trained and tracked ML models using MLflow for churn prediction and customer segmentation.
	•	Reporting: Connected Power BI with Databricks SQL to create interactive dashboards.
	•	CI/CD Friendly: Modular notebook structure supports reproducibility and scalability.

Tech Stack
	•	Databricks (Community Edition)
	•	PySpark & Spark SQL
	•	Delta Lake
	•	MLflow
	•	Power BI (external integration)
	•	Git for version control
