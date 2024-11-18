# Mobile Plan Analysis and Optimization

## Overview
This project analyzes mobile usage patterns and recommends optimal mobile plans based on 12 months of customer usage data. It evaluates data, minutes, and SMS usage to identify cost-effective solutions across multiple providers.

## Key Features
- Usage pattern visualization and analysis
- Plan cost optimization and comparison
- Statistical usage analysis (mean, median, max, min)
- Automated plan recommendations
- Interactive visualization tools

## Tech Stack
- Python 3.10.14
- Docker & Poetry
- Key Libraries: pandas, matplotlib, seaborn, numpy, scikit-learn
- Jupyter Notebooks

## Project Structure
src/
├── insights/
│   ├── CSV_files/
│   │   ├── Customer_Usage_Last_12_Months.csv
│   │   └── Mobile_Plans_Test_Data.csv
│   └── task_analysis/
│       ├── data_visualization.ipynb    
│       └── plan_calculator.ipynb       

## Analysis Components
1. **Data Visualization Notebook**
   - Time series analysis of usage patterns
   - Usage distribution analysis
   - Plan limit comparisons
   - Customer segmentation

2. **Plan Calculator Notebook**
   - Cost optimization algorithms
   - Plan comparison across providers
   - Usage statistics calculation
   - Best plan recommendations

## Quick Start
1. Install Docker Desktop and VS Code with Remote Containers
2. Clone repository
3. Open in container
4. Run Jupyter notebooks

## Author
- **Name:** Amer Alnajdawi
- **Email:** amernajdawi8@gmail.com
- **GitHub:** [amernajdawi/best_mobile_tariff](https://github.com/amernajdawi/best_mobile_tariff.git)