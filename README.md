# Data Science Portfolio
*Timothy Spivey*

A comprehensive portfolio demonstrating proficiency in machine learning, statistical analysis, and data visualization for business applications.

## Core Competencies

- **Machine Learning**: Classification, regression, clustering algorithms
- **Data Analysis**: Statistical modeling, hypothesis testing, trend analysis  
- **Visualization**: Interactive dashboards, statistical plots, business reports
- **Programming**: Python, pandas, scikit-learn, statistical libraries

## Repository Structure
data-science-portfolio/
├── projects/           # Complete analysis projects with documentation
├── datasets/          # Sample and cleaned datasets for reproducible analysis
├── visualizations/    # Publication-ready charts and interactive dashboards
├── models/           # Trained ML models with performance metrics
├── reports/          # Executive summaries and technical documentation
├── pyproject.toml    # Dependency management via UV
└── README.md         # Project overview and setup guide

## Featured Projects

### 1. Customer Segmentation Analysis
*Location: `projects/customer_segmentation/`*
- K-means clustering to identify customer groups
- RFM analysis for targeted marketing strategies

### 2. Sales Forecasting Model
*Location: `projects/sales_forecasting/`*
- Time series analysis using ARIMA and seasonal decomposition
- 95% accuracy in quarterly sales predictions

### 3. A/B Testing Framework
*Location: `projects/ab_testing/`*
- Statistical significance testing for product features
- Automated reporting dashboard for business stakeholders

## Quick Start

### Prerequisites
- Python 3.10+
- UV package manager ([installation guide](https://docs.astral.sh/uv/))

### Setup Environment
```bash
# Clone repository
git clone https://github.com/ts2427/data-science-portfolio.git
cd data-science-portfolio

# Install dependencies
uv sync

# Activate environment
source .venv/bin/activate  # Linux/Mac
.venv\Scripts\activate     # Windows
