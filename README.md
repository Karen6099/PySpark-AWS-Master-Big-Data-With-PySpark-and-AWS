# PySpark Big Data Learning Repository

A comprehensive collection of PySpark examples and notebooks covering RDD operations, DataFrame manipulations, ETL processes, collaborative filtering, and streaming.

## 📁 Project Structure

```
├── DF/                          # DataFrame Operations
│   ├── ComprehensiveDataFrameGuide.ipynb
│   ├── Project.ipynb
│   ├── Quiz1-4.ipynb
│   └── data files (StudentData.csv, OfficeData.csv, etc.)
├── RDD/                         # Resilient Distributed Datasets
│   ├── notebooks/
│   │   ├── Count.ipynb
│   │   ├── Map.ipynb
│   │   ├── Filter.ipynb
│   │   ├── WordCount.ipynb
│   │   └── 10+ more notebooks
│   └── data/
├── ETL/                         # Extract, Transform, Load
│   ├── ETL.ipynb
│   └── data files
├── Collaborative Filtering/     # Recommendation Systems
│   ├── collaborativeFiltering.ipynb
│   └── movie data (movies.csv, ratings.csv)
└── Spark Streaming/             # Real-time Processing
    ├── Streaming_RDD.ipynb
    ├── Streaming_DF.ipynb
    └── data/
```

## 🚀 Quick Start

### Prerequisites
- Python 3.11+
- Java 17+ (for PySpark)
- PySpark installed

### Installation
```bash
pip install pyspark jupyterlab
```

### Run Examples
```bash
jupyter lab
```
Open any `.ipynb` file and run the cells sequentially.

## 📚 Learning Modules

### 1. RDD Operations
- Basic transformations: `map`, `filter`, `flatMap`
- Aggregations: `reduceByKey`, `groupByKey`
- Actions: `count`, `collect`, `saveAsTextFile`
- Word count examples and quizzes

### 2. DataFrame Operations
- Creating DataFrames from CSV/RDD
- Schema management and data types
- Column operations: `select`, `withColumn`, `withColumnRenamed`
- Filtering and aggregations
- Comprehensive guide with examples

### 3. ETL Pipeline
- Extract: Reading text files
- Transform: Splitting, exploding, counting words
- Load: Saving to CSV (with PostgreSQL JDBC option)

### 4. Collaborative Filtering
- Movie recommendation system
- User-item rating analysis
- Matrix factorization concepts

### 5. Spark Streaming
- Real-time data processing
- DStream operations
- Structured Streaming with DataFrames

## 🎯 Key Features

- ✅ **Hands-on Examples**: Each concept demonstrated with working code
- ✅ **Progressive Learning**: From basic RDDs to advanced streaming
- ✅ **Real Datasets**: Movie ratings, student data, office data
- ✅ **Quizzes & Exercises**: Test your understanding
- ✅ **Production Ready**: Includes error handling and best practices

## 📖 Usage Tips

- Start with `RDD/notebooks/My First Notebook.ipynb` for basics
- Use `DF/ComprehensiveDataFrameGuide.ipynb` as DataFrame reference
- Run ETL pipeline in `ETL/ETL.ipynb` for complete workflow
- Check output files in respective directories after running notebooks

## 🔧 Troubleshooting

- **Java Errors**: Ensure Java 17+ is installed and `JAVA_HOME` is set
- **File Permission Issues**: Close CSV files before running notebooks
- **Memory Issues**: Reduce data size or increase Spark memory settings
- **PostgreSQL JDBC**: Download driver JAR for database connectivity

---

*Based on Udemy course: [PySpark & AWS: Master Big Data with PySpark and AWS](https://www.udemy.com/course/pyspark-aws-master-big-data-with-pyspark-and-aws/)*