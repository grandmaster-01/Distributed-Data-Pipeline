# Distributed Data Pipeline

A comprehensive distributed data processing pipeline built with **Apache PySpark** for analyzing e-commerce transaction data. This project demonstrates big data processing capabilities including data ingestion, quality validation, advanced analytics, customer segmentation, and machine learning models.

## 📋 Overview

This project implements a scalable data pipeline that processes 20,000+ sales transactions using PySpark's distributed computing framework. The pipeline includes interactive visualizations, SQL-based analytics, and machine learning models for regression and classification tasks.

## ✨ Features

- **Distributed Data Processing**: Leverages Apache Spark for efficient processing of large-scale transaction data
- **Data Quality Validation**: Automated data cleaning and validation pipelines
- **Advanced Analytics**:
  - High-value transaction filtering
  - Sales aggregation by category
  - Rolling average computations
  - Customer segmentation and ranking
- **Business Intelligence Queries**: SQL-based analytics for business insights
- **Interactive Visualizations**: Plotly-based exploratory data analysis (EDA)
- **Machine Learning Models**:
  - Linear Regression for sales prediction
  - Random Forest Regression
  - Deep Learning with Multi-layer Perceptron Classifier
  - Cross-validation and hyperparameter tuning
- **Data Export**: CSV export capabilities for processed results

## 📊 Data Schema

The pipeline processes sales transaction data with the following schema:

| Column          | Type   | Description                              |
|----------------|--------|------------------------------------------|
| transaction_id | String | Unique identifier for each transaction   |
| user_id        | Integer| Customer identifier                      |
| category       | String | Product category (Electronics, Clothing, Home, Sports, Books) |
| amount         | Float  | Transaction value                        |
| timestamp      | String | Transaction timestamp (YYYY-MM-DDTHH:MM:SS) |

**Sample Dataset**: 20,000 synthetic sales transactions across 5 product categories

## 🛠️ Technologies Used

- **Apache Spark (PySpark)**: Distributed data processing framework
- **Spark SQL**: Structured data queries
- **Spark MLlib**: Machine learning library
- **Plotly**: Interactive data visualizations
- **Python**: Core programming language
- **Jupyter Notebook**: Interactive development environment

## 📁 Project Structure

```
Distributed-Data-Pipeline/
├── README.md
├── LICENSE
└── Distributed Data Pipeline/
    ├── Pyspark.ipynb                             # Main pipeline notebook
    ├── sales_transactions.csv                    # Sample transaction data (20K records)
    ├── Distributed Data Processing Pipeline.pptx # Project presentation
    └── 24PG00021_Big_Data.pdf                   # Project documentation
```

## 🚀 Prerequisites

- Python 3.7+
- Apache Spark 3.x
- Java 8 or 11 (required for Spark)
- Jupyter Notebook or JupyterLab

### Required Python Packages

```
pyspark
plotly
pandas
numpy
```

## 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/grandmaster-01/Distributed-Data-Pipeline.git
cd Distributed-Data-Pipeline
```

2. Install Apache Spark (if not already installed):
```bash
# For Ubuntu/Debian
sudo apt-get update
sudo apt-get install default-jdk
pip install pyspark
```

3. Install required Python packages:
```bash
pip install pyspark plotly pandas numpy jupyter
```

## 💻 Usage

1. Navigate to the project directory:
```bash
cd "Distributed Data Pipeline"
```

2. Launch Jupyter Notebook:
```bash
jupyter notebook Pyspark.ipynb
```

3. Run the cells sequentially to:
   - Initialize the Spark session
   - Load and validate the transaction data
   - Perform data quality checks
   - Execute analytics and transformations
   - Train machine learning models
   - Generate interactive visualizations
   - Export processed results

## 📈 Pipeline Workflow

1. **Initialize**: Setup SparkSession and configure environment
2. **Load Data**: Ingest transaction data from CSV
3. **Data Quality**: Validate schema and clean data
4. **Analysis**: 
   - Filter high-value transactions
   - Aggregate sales by category
   - Compute rolling averages
5. **Advanced Features**:
   - Customer segmentation with ranking
   - Business SQL queries
6. **Interactive EDA**: Visualize distributions and trends
7. **Machine Learning**: Train and evaluate predictive models
8. **Export**: Save results to CSV format

## 🎯 Use Cases

- **E-commerce Analytics**: Analyze sales patterns and customer behavior
- **Business Intelligence**: Generate insights for strategic decision-making
- **Predictive Analytics**: Forecast sales and transaction trends
- **Customer Segmentation**: Identify high-value customers and segments
- **Data Engineering**: Demonstrate distributed data processing capabilities

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

## 📧 Contact

For questions or feedback, please open an issue in the repository.