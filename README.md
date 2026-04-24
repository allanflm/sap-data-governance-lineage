# SAP Data Governance & Lineage Validation

## 📊 Overview

This project provides a data governance solution using PySpark and Databricks to monitor table usage and validate business control against real data lineage.

## 🎯 Objectives

* Identify unused tables
* Detect inconsistencies between business control and actual usage
* Prevent production issues caused by incorrect table deactivation
* Improve data governance and observability

## 🧠 Architecture

* Business Layer: Excel / CSV control file
* Technical Layer: Databricks system table lineage
* Validation Layer: PySpark transformations

## 🚀 Features

* Table usage analysis
* Lineage-based validation
* Detection of inactive but used tables
* Identification of cleanup candidates

## 🛠️ Technologies

* PySpark
* Databricks
* Delta Lake
* Data Lineage

## 📈 Future Improvements

* Automated daily monitoring
* Alert system
* Dashboard visualization
