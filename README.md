# IMPC_SQL_Database
The International Mouse Phenotyping Consortium (IMPC) Phenotypic Data Cleaning, Annotation, and Visualization

This project showcases a complete data management and visualization workflow using IMPC mouse phenotype data. It includes data cleaning in R, MySQL database design and annotation, SQL querying, and interactive visualization via an R Shiny dashboard.

---

## Overview

The goal of this project is to transform and analyze phenotypic data from the International Mouse Phenotyping Consortium (IMPC) to support genotype-phenotype exploration. The workflow includes data collation and cleaning, MySQL schema creation, genotype-based querying, and visual exploration through a Shiny web application. The resulting tools enable researchers to retrieve statistically significant phenotype associations and uncover patterns across gene knockouts.

---

## Objectives

- Clean and standardize over 190,000 phenotype-genotype records from raw CSV files.
- Build a normalized relational **MySQL database** supporting efficient queries.
- Annotate phenotype parameters by grouping them into biologically meaningful categories.
- Execute genotype-driven SQL queries to retrieve statistical insights.
- Develop an **R Shiny dashboard** to visualize:
  - Significant phenotypes per gene
  - Genes associated with a selected phenotype
  - Clusters of genes with similar phenotype profiles

---

## Tools & Technologies

- **Languages:** R, SQL, Shell
- **Environment:** Linux, command-line interface

---

## Workflow Components

- 1. Data Cleaning (R)
- 2. SQL Database Annotation
- 3. Genotype Querying (SQL)
- 4. R Shiny Dashboard
---

## Dashboard Visualizations

- Bar plots for significant phenotypes per gene and vice versa
- PCA-based clustering of genes linked to human diseases
- Interactive tooltips for detailed exploration

---

## Data Source

Data provided by the **International Mouse Phenotyping Consortium (IMPC)**  
📎 [https://www.mousephenotype.org/](https://www.mousephenotype.org/)


