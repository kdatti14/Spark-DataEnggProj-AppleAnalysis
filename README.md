# Spark-DataEnggProj-AppleAnalysis
## Apache Spark End-To-End Data Engineering Project | Apple Data Analysis

### Objectives

The primary goal of this project was to design, implement, and analyze a scalable data pipeline using Apache Spark and PySpark within Databricks. The focus was on deriving actionable business insights from Apple sales data by examining customer purchase patterns and product performance.

### Key Highlights

- **Technologies Used**: Apache Spark, PySpark, Databricks.
- **Dataset**: Apple sales data with customer, order, product, and sales information.
- **End-to-End Data Engineering Approach**:
  - Data ingestion and transformation pipelines.
  - Analytics and insights generation.
  - Factory pattern implemented to streamline code modularity and reusability.

### Insights Derived

1. **Analyzing Customers**: Identified customers who purchased AirPods after buying iPhones.
2. **Purchase Patterns**: Analyzed customers who bought both AirPods and iPhones.
3. **Post-Purchase Products**: Listed all products purchased by customers after their initial purchase.
4. **Average Purchase Delay**: Calculated the average time delay in buying AirPods after purchasing an iPhone for each customer.
5. **Top-Selling Products**: Identified the top 3 selling products in each category by revenue.

### Project Summary

This project demonstrates building an end-to-end data engineering pipeline in a real-world scenario using Apache Spark and Databricks. The workflow includes data ingestion, transformation, and analytics with a focus on optimized performance and scalability.

- **Source Data**: CSV files converted to Parquet and Delta tables for efficient querying and ACID compliance.
- **Transformation Techniques**: Used Spark SQL, DataFrame APIs, and advanced operations like window functions, joins, and filters, leveraging the Factory pattern for modular and maintainable code implementation.
- **Optimization**: Applied partitioning, bucketing, and broadcast joins to improve processing efficiency.
- **Pipeline Implementation**:
  - Extracted and transformed data to generate meaningful insights.
  - Leveraged Delta tables for structured storage and transaction management.
- **Integration**: Pipelines were designed to integrate seamlessly with cloud storage systems such as AWS S3 and Google Cloud.

### Key Takeaways

- Real-world application of Apache Spark and PySpark in Databricks.
- Scalable and reusable pipeline design for data engineering use cases.
- Practical insights into purchase patterns and product performance.




 
