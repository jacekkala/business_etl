# **Business Data Warehouse & Power BI Analytics**  

## **Overview**  
This project demonstrates the design and implementation of a **SQL-based Data Warehouse** with a structured **ETL pipeline**, optimized for sales analytics. The data is processed through **Bronze, Silver, and Gold layers**, ensuring quality and business-ready insights. The final data is analyzed in SQL scripts and visualized in a **Power BI dashboard** for trend analysis and decision-making.

## **Data Architecture**  
![Data Architecture](data_architecture.png)  

## **Dashboard Preview**  
![Sales Dashboard](https://github.com/user-attachments/assets/52936858-8983-495f-9ad5-43dcbd1994da)

## **Key Features**  
- **SQL Data Warehouse:** Implemented a **star-schema model** with well-structured fact and dimension tables.  
- **ETL Pipeline:** Automated **data ingestion, transformation, and cleansing** via stored procedures.  
- **Power BI Report:** Built an interactive **sales performance dashboard**, providing insights into revenue, customers, and trends.  
- **Data Quality Checks:** Ensured accuracy with referential integrity constraints and anomaly detection.  
- **Business Impact:** Enabled data-driven decision-making by identifying **sales trends, top products, and high-value customers**.  

## **Technologies Used**  
- **Microsoft SQL Server** (for database and ETL processing)  
- **Microsoft Power BI** (for reporting and visualization)

## **Project Structure**  
```
├── data/                               # Input datasets (ERP and CRM data)
│
├── data_analysis/                      # SQL scripts analyzing business-ready data
│   ├── sales_report.pbix               # File containing Power BI report
|
├── docs/                               # Project documentation
│   ├── README.md                       # Data catalog for gold layer
│
├── etl_scripts/                        # SQL scripts for ETL and transformations
│   ├── bronze/                         # Scripts for extracting and loading raw data
│   ├── silver/                         # Scripts for cleaning and transforming data
│   ├── gold/                           # Scripts for constructing analytical models
│
├── etl_tests/                          # Test scripts and quality files for ETL process

├── init_datawarehouse.sql              # Data warehouse initialization file
├── README.md                           # Project overview and description
```

## **Getting Started**  
1. **Setup the Database:** Execute the provided SQL scripts to create and populate the Data Warehouse.  
2. **Run the ETL Process:** Use the stored procedures to load and transform data across Bronze, Silver, and Gold layers.  
3. **Load the Power BI Report:** Open the `.pbix` file and connect it to the SQL database.  
4. **Explore Insights:** Analyze sales performance and trends through the interactive dashboard and SQL analysis scripts.  
