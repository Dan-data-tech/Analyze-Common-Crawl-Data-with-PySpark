# PySpark and Big Data Project

## Overview
This project focuses on analyzing data from the **Common Crawl** using PySpark. It includes multiple tasks that demonstrate the use of Resilient Distributed Datasets (RDDs) to perform various transformations and analyses on a domain graph dataset.

## Tasks Breakdown
### Task Group 1: Analyzing Common Crawl Data with RDDs

- **Task 1:** Initialize a new Spark Context and read the domain graph as an RDD.
- **Task 2:** Format the raw data using a custom function (`fmt_domain_graph_entry`) and create a new RDD of formatted domain counts.
- **Task 3:** Extract subdomain counts from the formatted data and store them in a new RDD.

## Project Structure
The notebook is structured with code cells and explanations for each task. Below are the major sections:

1. **Setting up the environment:**
   - Initialize a SparkSession and SparkContext.
   
2. **Reading Data:**
   - Load the domain graph from a CSV file into an RDD.
   
3. **Transformations:**
   - Apply transformations to the RDD, such as formatting the data and extracting subdomain counts.
   
4. **RDD Operations:**
   - Perform common RDD operations like `map`, `take`, and `save`.

## Dataset
The project uses a CSV file (`cc-main-limited-domains.csv`) from the Common Crawl dataset. This file contains domain graph data, including site IDs, domains, top-level domains (TLDs), and subdomain counts.

## Setup Instructions
### Prerequisites:
- Python 3.x
- Apache Spark
- PySpark library
- Jupyter Notebook

## Future Improvements
- Expanding the analysis to other Common Crawl datasets.
- Implementing additional RDD operations and transformations.
- Visualizing the results using data visualization libraries.
