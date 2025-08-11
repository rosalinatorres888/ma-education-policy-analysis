# 📊 Massachusetts Education Policy Analysis: ML-Driven Insights for Strategic Decision Making

<div align="center">

![Python](https://img.shields.io/badge/python-v3.9+-blue.svg)
![scikit-learn](https://img.shields.io/badge/scikit--learn-1.3.0-orange.svg)
![SHAP](https://img.shields.io/badge/SHAP-0.42.1-red.svg)
![Plotly](https://img.shields.io/badge/Plotly-5.15.0-green.svg)
![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Status](https://img.shields.io/badge/status-Active-success.svg)

**Using Machine Learning and Causal Inference to Decode Educational Excellence**

[View Demo](https://your-streamlit-app.streamlit.app) | [Documentation](notebooks/) | [Report Issue](https://github.com/rosalinatorres888/ma-education-policy-analysis/issues)

</div>

---

## 🎯 Executive Summary

This project leverages **advanced machine learning techniques** and **interpretable AI** to analyze what makes Massachusetts the #1 state in education nationwide. Through comprehensive data analysis, feature engineering, and counterfactual modeling, I provide actionable policy recommendations with quantified ROI estimates.

### 🔑 Key Question
**How can strategic investment in education policy maximize both academic outcomes and economic returns?**

### 💡 Core Findings
- Massachusetts outperforms the national average by **19 points** in 8th grade reading (NAEP 2024)
- **4.2x ROI** on early childhood education investment (highest confidence: 92%)
- Bachelor's degree attainment (45.7%) exceeds national average by **12 points**
- Comprehensive reform can improve scores by **15.6 points**

---

## ✨ Features

### 🤖 Advanced ML/AI Capabilities
- **Ensemble Learning**: Random Forest, Gradient Boosting, ElasticNet models
- **Interpretable AI**: SHAP (SHapley Additive exPlanations) for model transparency
- **Counterfactual Analysis**: Optimization algorithms to find minimal policy changes
- **Feature Engineering**: 20+ engineered features including polynomial and interaction terms
- **Uncertainty Quantification**: Prediction intervals using ensemble methods

### 📊 Data-Driven Insights
- **Verified Government Data**: NAEP 2024, U.S. Census ACS 2023, BEA GDP data
- **Cross-Validation**: 5-fold CV with R² = 0.875 (±0.042)
- **Policy Simulations**: What-if analysis for 6 different intervention scenarios
- **Interactive Visualizations**: Plotly dashboards for real-time exploration

---

## 🚀 Quick Start

### Prerequisites
- Python 3.9+
- pip or conda package manager

### Installation

```bash
# Clone the repository
git clone https://github.com/rosalinatorres888/ma-education-policy-analysis.git
cd ma-education-policy-analysis

# Create virtual environment (recommended)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the analysis
python run_analysis.py

# Launch interactive dashboard (optional)
streamlit run app/dashboard.py

## 📈 Results & Key Findings

### Model Performance Metrics

| Metric | Value | Description |
|--------|-------|-------------|
| **R² Score** | 0.875 (±0.042) | Explains 87.5% of variance in education scores |
| **RMSE** | 3.2 points | Average prediction error |
| **MAE** | 2.4 points | Mean absolute error |
| **Cross-Validation** | 5-fold | Consistent performance across folds |

### Feature Importance (SHAP Analysis)
