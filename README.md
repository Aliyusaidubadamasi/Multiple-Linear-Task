# Multiple Linear Regression - Multi-Channel Marketing Analysis

## Project Overview
This project analyzes a multi-channel marketing dataset using Multiple Linear Regression to determine which marketing channels have the most significant impact on Sales.

## Dataset Description
- **TV**: TV advertising spend category (Low, Medium, High)
- **Radio**: Radio advertising spend ($)
- **Social Media**: Social media advertising spend ($)
- **Influencer**: Influencer type (Micro, Mega, Nano, Macro)
- **Sales**: Total sales generated ($)

## Key Findings
- **Adjusted R-squared**: 0.985 (98.5% of variance explained)
- **Best Performing Channel**: Radio
- **Radio ROI**: $3.70 per $1 spent
- **TV**: Higher TV spend categories strongly correlate with increased Sales
- **Influencer**: Mega and Macro influencers show stronger results

## Setup Instructions

### Prerequisites
- Python 3.7+
- Jupyter Notebook or Google Colab

### Install Required Libraries
```bash
pip install pandas numpy matplotlib seaborn statsmodels scipy
