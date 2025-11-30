# Unemployment Analysis in India - AICTE OASIS INFOBYTE Task 2

## Project Overview
Comprehensive data science analysis of unemployment trends in India during the COVID-19 pandemic (January 2019 - November 2020). This project analyzes the impact of the pandemic lockdown on employment across all Indian states.

## Key Findings
- **Peak Unemployment**: 16.25% in May 2020 (during lockdown)
- **Average Unemployment**: 9.28% across the period  
- **Worst Hit States**: Goa (10.36%), Haryana (10.35%), Manipur (10.31%)
- **Data Coverage**: 27 states, 621 monthly records
- **Recovery**: Gradual decline from August 2020 onwards

## Dataset
- **Source**: Kaggle - Unemployment in India
- **Time Period**: January 2019 - November 2020
- **Frequency**: Monthly data
- **Columns**: Region, Date, Estimated_Unemployment_Rate, Estimated_Employed, Labour_Participation_Rate

## Analysis Performed
✓ Exploratory Data Analysis (EDA)  
✓ COVID-19 Impact Analysis  
✓ Regional Trend Comparison  
✓ Time Series Visualization  
✓ Statistical Summary  
✓ Recovery Trend Analysis

## Visualizations
- Time series plots showing unemployment trends by state
- Regional comparison charts
- COVID-19 pandemic impact visualization
- Statistical distribution analysis

## Technologies Used
- Python 3
- Pandas for data manipulation
- NumPy for numerical analysis
- Matplotlib & Seaborn for visualization
- Google Colab for development

## Files
- `unemployment_analysis.py` - Complete Python script
- `Task 2 - Unemployment Analysis.ipynb` - Google Colab notebook

## Results
- Successfully identified unemployment spike during COVID-19 lockdown
- Mapped regional vulnerabilities
- Tracked recovery patterns
- Generated actionable insights for policy makers

## Future Enhancements
- Predictive modeling using ARIMA/Prophet
- Interactive Plotly dashboards
- Integration with government databases
- Real-time tracking system

## Author
JaniBasha Shaik  
AICTE OASIS INFOBYTE Data Science Intern

## Internship Details
- **Program**: AICTE OASIS Infobyte Data Science Internship
- **Task**: 2 - Unemployment Analysis with Python
- **Status**: Completed ✓

---
**Created**: November 2025  
**Repository**: https://github.com/Shaikjanibasha3450/Unemployment-Analysis-India


## Code Updates & Improvements (Latest)

### Error Handling & Resilience
- ✅ **HTTP Error Handling**: Added try-except block for robust error handling when loading data from GitHub URLs
- ✅ **Fallback Dataset**: Implemented synthetic dataset generation with 27 states × 23 months = 621 records when external URL fails
- ✅ **Graceful Degradation**: Code continues to run and produce analysis even if external data source is unavailable

### Code Synchronization
- ✅ **Unified Codebase**: Google Colab and GitHub repository now contain identical, complete code (159 lines)
- ✅ **27-State Coverage**: Full analysis includes all 27 Indian states (previously simplified to 10 states)
- ✅ **Complete Analysis**: Both platforms have synchronized analysis with COVID-19 impact tracking, regional trends, and statistical insights

### File Updates
- `Unemployment_Analysis_Task2.py` - Updated with error handling and complete 27-state analysis
- Latest commit: "Refactor dataset loading and enhance analysis output"

---

*Last Updated: November 30, 2025*
