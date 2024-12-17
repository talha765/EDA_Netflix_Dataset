# Spark EDA Assignment

## Overview
This project performs Exploratory Data Analysis (EDA) on the Netflix Movies & TV Shows dataset using **PySpark** for data processing and **Docker** for environment setup. Key insights were extracted and visualized using **Pandas** and **Matplotlib**.

## Tools & Technologies
- **PySpark**: For large-scale distributed data processing.
- **Docker**: To create an isolated environment for Spark.

## Project Workflow
1. **Environment Setup**:
   - Docker container was used to set up the Spark environment.
   - Commands to run Docker and initiate Spark.
2. **Data Cleaning & Transformation**:
   - Processed date formats, handled null values, and extracted year-based columns.
3. **Analysis & Visualization**:
   - Performed EDA to explore key metrics like content type, country, rating, and year of release.
   - Used PySpark for computation and Pandas/Matplotlib for graph-based visualizations.

## Key Insights
- Counted unique values for categorical columns.
- Identified the top 5 countries with the most content.
- Extracted trends in content releases by year.

## How to Run
1. **Start Docker container** with Spark installed.
   ```bash
   docker run -it --rm -p 8888:8888 jupyter/pyspark-notebook
   ```
2. **Run the PySpark script** inside the Docker container.
   ```bash
   spark-submit eda_script.py
   ```

## Conclusion
This project demonstrates the use of PySpark for scalable EDA and Docker for an efficient development environment. Key insights were visualized using Pandas and Matplotlib to support data-driven decision-making.

