# Stock Market Performance & Risk Analytics Dashboard

## Table of Contents

- [Purpose](#purpose)
- [System Requirements](#system-requirements)
- [Installation Guide](#installation-guide)
- [Features and Project Walkthrough](#features-and-project-walkthrough)
- [Design Decisions](#design-decisions)
- [Business Use Case](#business-use-case)
- [Future Enhancements](#future-enhancements)
- [Author](#author)

## Purpose

Stock Market Performance & Risk Analytics Dashboard is a multi-layered Power BI financial analytics solution designed to evaluate stock performance, risk exposure, and investment insights.

The project transforms raw financial datasets into a structured, interactive, and decision-oriented dashboard enabling:

- Industry-level performance analysis  
- Individual stock comparison  
- Profitability and risk evaluation  
- Interactive filtering using slicers  
- Logical analytical navigation across report layers  

This project demonstrates strong capabilities in:

- Data modeling  
- DAX calculations  
- Dashboard storytelling  
- Financial data analysis  

## System Requirements

Before running the project locally, ensure the following:

- **Power BI Desktop (Latest Version)** – Required to open and interact with the `.pbix` file.  
- **Git** – Required to clone the repository.  
- Windows OS recommended (Power BI Desktop support).  

Download Power BI Desktop from:  
https://powerbi.microsoft.com/

## Installation Guide

### 1. Clone the Repository

```bash
git clone https://github.com/parikipandlasujeeth-hub/Stock_Market_Performance.git
```

### 2. Open the Power BI File

- Download `Final_Exam_Project.pbix`
- Open it using Power BI Desktop
- Interact with slicers and navigation buttons

## Features and Project Walkthrough

### 1. Executive Summary Dashboard

Provides a high-level performance overview.

- KPI Cards (Total Volume, Avg Closing Price, Daily Change)
- Industry comparison visuals
- Clustered Bar Charts
- Interactive slicers
- Executive-ready clean layout

<img width="1336" height="1040" alt="executive-summary" src="https://github.com/user-attachments/assets/d8f26f84-237c-4052-9427-20b25be3fbb5" />


### 2. Stock Performance Analysis

Detailed stock-level breakdown.

- Volatility classification (Low vs High)
- Pie chart for volatility distribution
- Tabular stock metrics
- Dynamic filtering by symbol

<img width="1332" height="1043" alt="stock-performance" src="https://github.com/user-attachments/assets/3fb5c005-c74b-4c91-9c93-be33066cb46e" />


### 3. Advanced Market Insights

Advanced financial analytics and pivot-style analysis.

- Percentage change comparison
- Risk vs Return indicators
- Calculated performance ratios
- Advanced DAX-driven measures
- Symbol-based filtering

<img width="1342" height="1053" alt="advanced-insights" src="https://github.com/user-attachments/assets/3ea08752-18a2-4f2a-b94b-5645fd49ebe3" />


## Design Decisions

### Technology Stack

- Power BI Desktop  
- Power BI Service  
- DAX (Data Analysis Expressions)  
- Multi-source dataset integration  

### Data Modeling

- Imported and connected multiple datasets  
- Established relational data model  
- Optimized relationships for accurate aggregation  

### Measures (DAX)

- 4+ measures created  
- Advanced measures using VAR variables  
- Reusable KPI calculations  
- Organized measures into dedicated folder  

### Calculated Columns

- 3+ calculated columns  
- Unique logic per column  
- Derived financial ratios and categorical insights  

### Report Architecture

The dashboard is structured in three logical layers:

1. Executive Overview  
2. Stock-Level Comparison  
3. Deep Financial Insights  

Each page includes navigation buttons for seamless user experience.

### Visualization Principles

- Clear hierarchy of information  
- High-contrast readable fonts  
- Logical grouping of metrics  
- Conditional formatting for clarity  
- Clean executive-ready layout

## Business Use Case

This dashboard enables:

- Quick executive-level performance assessment
- Comparative stock analysis
- Risk exposure evaluation
- Industry-level benchmarking
- Data-driven investment insights

The analytical progression follows:

**Industry Overview → Stock Comparison → Advanced Risk Insights**

## Future Enhancements

- Real-time stock API integration  
- Volatility and Sharpe ratio calculations  
- Automated data refresh pipelines  
- Scenario simulation dashboard  
- Predictive analytics layer

## Repository Structure

```
Stock-Market-Performance-Dashboard/
│
├── Final_Exam_Project.pbix
├── Final_Exam_Project.pptx
├── QR_Code_Screenshot.jpg
└── README.md
```

## Author

**Sujeeth Parikipandla**  
Graduate Student – Business Analytics  
Focused on Financial Analytics, Data Visualization & Business Intelligence
