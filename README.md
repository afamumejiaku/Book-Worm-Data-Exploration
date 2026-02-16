# Project Book-Worm - Data Exploration

## Overview
This repository contains a comprehensive data exploration analysis for the Book-Worm Dataset. The analysis examines 3 years of weekly marketing data across 7 media channels to assess data readiness and uncover key insights.

## Files Included
- `01_mmm_data_exploration.ipynb` - Main data exploration notebook
- `MediaSpend.xlsx` - Media channel spend data (157 weeks)
- `ProjectInputData.xlsx` - KPI and performance metrics data (157 weeks)

## Dataset Summary
- **Time Period**: January 2022 - December 2024 (157 weeks)
- **Media Channels**: 7 channels
  - YouTube ($2.75M total spend)
  - Meta ($2.20M total spend)
  - Google Generic Paid Search ($2.07M total spend)
  - Google Branded Paid Search ($1.78M total spend)
  - TV ($714K total spend)
  - Google Display ($264K total spend)
  - Influencers ($17K total spend)
- **KPI**: Account Subscriptions (903,070 total)
- **Control Variables**: School holidays, promotions, competitor activity

## Data Quality
✅ **All checks passed:**
- No missing values
- Consistent weekly granularity
- Aligned dates across files
- Sufficient time period (3 years)
- Multiple performance metrics
- Control variables included

## Notebook Contents

### 1. Data Loading & Overview
- Initial data inspection
- Schema validation
- Date range confirmation

### 2. Data Quality Assessment
- Missing value check
- Date alignment verification
- Frequency validation

### 3. Target Variable Analysis (KPI)
- Account subscriptions trends
- Distribution analysis
- Seasonal patterns
- Year-over-year growth

### 4. Media Spend Analysis
- Channel-wise spend breakdown
- Temporal trends
- Budget allocation
- Spend distribution

### 5. Media Performance Metrics
- Impressions, clicks, GRPs analysis
- Cost efficiency metrics (CPM, CPC, CPV)
- Performance trends over time

### 6. Correlations & Relationships
- Correlation with target variable
- Cross-channel relationships
- Scatter plots with trend lines
- Correlation heatmaps

### 7. Seasonality & Trends
- Monthly patterns
- Quarterly analysis
- School holiday impact
- Promotion effects

### 8. Control Variables
- Holiday impact analysis
- Competitor promotion effects
- Internal promotion analysis

### 9. Data Readiness for MMM
- Comprehensive checklist assessment
- MMM requirement validation
- Recommendations

### 10. Key Insights & Next Steps
- Summary of findings
- Data quality confirmation
- Recommended modeling approaches

## How to Run

### Prerequisites
```bash
pip install pandas numpy matplotlib seaborn openpyxl jupyter
```

### Running the Notebook
```bash
jupyter notebook 01_mmm_data_exploration.ipynb
```

Or use JupyterLab:
```bash
jupyter lab
```

## Key Insights

### 📊 Data Characteristics
- **157 weeks** of complete data (ideal for MMM - exceeds 2-year minimum)
- **Zero missing values** across all variables
- **7 media channels** with varying investment levels
- **Strong data quality** - ready for immediate MMM implementation

### 💰 Spend Insights
- Total marketing investment: **$9.79M** over 3 years
- Top 3 channels: YouTube (28%), Meta (22%), Generic Search (21%)
- Significant spend variation across channels enabling attribution

### 📈 KPI Performance
- Average weekly subscriptions: **5,752**
- Total subscriptions: **903,070** over 3 years
- Observable growth trends and seasonal patterns

### 🔍 Correlations
- Multiple channels show positive correlation with subscriptions
- Control variables (holidays, promotions) show measurable impact
- Data supports causal inference modeling


## Visualizations Generated

The notebook creates several publication-quality visualizations:
- KPI trends and distributions
- Media spend allocation charts
- Channel-specific performance trends
- Correlation heatmaps
- Seasonal pattern analysis
- Efficiency metrics over time
- Control variable impacts

## For Hiring Managers

This notebook demonstrates:
- **Data literacy**: Comprehensive understanding of relevant data requirements
- **Statistical analysis**: Correlation, distribution, trend analysis
- **Visualization skills**: Clear, professional charts and insights
- **Domain knowledge**: Understanding of marketing metrics and KPIs
- **Communication**: Well-documented code and clear insights

## Author
Umejiaku Afamefuna

## Date
February 2026

## License
This is a demonstration project for employment consideration.

---
