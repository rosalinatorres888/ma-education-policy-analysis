
---

# 📊 Massachusetts Education Policy Analysis: Data-Driven Insights for Strategic Investment

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://www.python.org/downloads/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Data: Government](https://img.shields.io/badge/Data-Government%20Sources-green.svg)](https://www.naep.gov)
[![Live Demo](https://img.shields.io/badge/Live-Presentation-ff69b4.svg)](https://rosalinatorres888.github.io/ma-education-policy-analysis/)

<div align="center">
  <h2>
    🌐 <a href="https://rosalinatorres888.github.io/ma-education-policy-analysis/">View Live Interactive Presentation</a> | 
    📊 <a href="https://github.com/rosalinatorres888/ma-education-policy-analysis">GitHub Repository</a>
  </h2>
</div>

## 🎯 Executive Summary

This repository contains a comprehensive data-driven analysis of Massachusetts education policy, leveraging machine learning and advanced analytics to uncover actionable insights for maximizing both academic outcomes and economic returns on educational investment.

**🔗 Quick Access:**
- [**View Live Presentation**](https://rosalinatorres888.github.io/ma-education-policy-analysis/) - Interactive web visualization
- [**GitHub Repository**](https://github.com/rosalinatorres888/ma-education-policy-analysis) - Source code and data
- [**Download Report**](reports/executive_summary.pdf) - Executive summary PDF

**Key Question:** How can strategic investment in Massachusetts education policy maximize both academic outcomes and economic returns?

> "Education is the seed of opportunity—sown wisely, it grows not only minds but thriving economies."

## 🚀 Key Findings

### Academic Excellence
- **National Leadership:** Massachusetts ranks **#1 nationally** across all NAEP 2024 assessments
- **Performance Gap:** Notable 19-point advantage in 8th grade reading compared to national average
- **Higher Education:** Bachelor's degree attainment (45.7%) exceeds national average by 12 percentage points

### Economic Impact
- **Fair Share Amendment:** Generated **$2.2B** in verified revenue (FY2024) for education and infrastructure
- **ROI Analysis:** Evidence-based estimates show **4.2x return** on early childhood education investment
- **GDP Correlation:** Strong positive correlation between educational attainment and state GDP per capita

## 📈 Performance Metrics Dashboard

| Indicator | Massachusetts | National Average | Difference | National Rank |
|-----------|--------------|------------------|------------|---------------|
| **4th Grade Math** | 246 | 235 | +11 | #1 |
| **8th Grade Math** | 283 | 273 | +10 | #1 |
| **4th Grade Reading** | 230 | 216 | +14 | #1 |
| **8th Grade Reading** | 279 | 260 | +19 | #1 |

## 🔬 Technical Approach

### Data Pipeline
```
Raw Data → Cleaning → Feature Engineering → ML Models → Insights → Policy Recommendations
```

### Machine Learning Models Employed
- **Predictive Modeling:** Random Forest and XGBoost for outcome prediction
- **Causal Inference:** Difference-in-Differences for policy impact assessment
- **Time Series Analysis:** ARIMA and Prophet for trend forecasting
- **Clustering:** K-means for district segmentation and resource allocation optimization

### Data Sources
- **NAEP 2024:** National Assessment of Educational Progress
- **Massachusetts DOR:** Fair Share Amendment financial data
- **U.S. Census ACS 2023:** American Community Survey demographics
- **BEA:** Bureau of Economic Analysis GDP data
- **DESE:** Massachusetts Department of Elementary and Secondary Education

### Analytical Techniques
- Multi-dimensional correlation analysis with Pearson and Spearman coefficients
- Conservative ROI estimation using Monte Carlo simulation
- Feature importance analysis for policy lever identification
- Cross-validation with peer-reviewed academic research

## 📁 Repository Structure

```
ma-education-policy-analysis/
│
├── 📊 data/
│   ├── raw/                 # Original datasets from government sources
│   ├── processed/            # Cleaned and transformed data
│   └── external/             # Supplementary datasets
│
├── 📓 notebooks/
│   ├── 01_data_exploration.ipynb
│   ├── 02_feature_engineering.ipynb
│   ├── 03_ML_modeling.ipynb
│   └── 04_policy_analysis.ipynb
│
├── 🐍 src/
│   ├── data_processing/     # Data cleaning and transformation scripts
│   ├── models/               # ML model implementations
│   ├── visualization/        # Plotting and dashboard generation
│   └── utils/                # Helper functions and utilities
│
├── 📊 visuals/
│   ├── charts/               # Static visualizations
│   ├── dashboards/           # Interactive dashboards
│   └── infographics/         # Policy-focused visual summaries
│
├── 📄 reports/
│   ├── technical_report.pdf  # Detailed methodology and findings
│   ├── executive_summary.pdf # High-level insights for stakeholders
│   ├── presentations/        # Slide decks for various audiences
│   └── 🌐 [Live Web Presentation](https://rosalinatorres888.github.io/ma-education-policy-analysis/)
│
├── 🧪 tests/                 # Unit tests for data validation
├── requirements.txt          # Python dependencies
├── config.yaml              # Configuration parameters
├── README.md                # This file
└── LICENSE                  # MIT License

```

## 🛠️ Installation & Setup

### Prerequisites
- Python 3.9+
- Jupyter Notebook/Lab
- Git

### Quick Start

#### 🌐 View Online
Visit the [**Live Interactive Presentation**](https://rosalinatorres888.github.io/ma-education-policy-analysis/) for immediate access to visualizations and insights.

#### 💻 Run Locally
```bash
# Clone the repository
git clone https://github.com/rosalinatorres888/ma-education-policy-analysis.git
cd ma-education-policy-analysis

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter
jupyter notebook
```

## 💻 Technologies Used

### Core Stack
- **Python 3.9+** - Primary programming language
- **Pandas & NumPy** - Data manipulation and analysis
- **Scikit-learn** - Machine learning models
- **XGBoost** - Gradient boosting for predictive modeling
- **Statsmodels** - Statistical testing and econometrics

### Visualization
- **Matplotlib & Seaborn** - Statistical visualizations
- **Plotly** - Interactive dashboards
- **Folium** - Geospatial mapping
- **GitHub Pages** - [Live web presentation hosting](https://rosalinatorres888.github.io/ma-education-policy-analysis/)

### Development Tools
- **Jupyter Notebooks** - Interactive development
- **Git/GitHub** - Version control
- **Docker** - Containerization (optional)

## 🎯 Policy Recommendations

Based on our ML-driven analysis, we recommend:

1. **🌱 Expand Universal Early Childhood Education**
   - Target underserved communities with highest predicted impact
   - Estimated ROI: 4.2x over 10-year period

2. **💰 Optimize Fair Share Funding Allocation**
   - ML model suggests 60/40 split between direct education and infrastructure
   - Focus on districts with highest marginal benefit potential

3. **🎓 Accelerate Bachelor's Degree Attainment**
   - Target: 50% by 2030 (from current 45.7%)
   - Focus on community college transfer pathways

4. **🔬 Scale STEM Initiatives**
   - Align with Massachusetts' innovation economy clusters
   - Predictive model shows 15% wage premium for STEM graduates

5. **🏘️ Integrated Poverty Intervention**
   - Combine education programs with social services
   - Multi-factor model shows synergistic effects

## 📊 Model Performance Metrics

| Model | Task | Accuracy | F1-Score | RMSE |
|-------|------|----------|----------|------|
| Random Forest | Outcome Prediction | 0.89 | 0.87 | - |
| XGBoost | Performance Classification | 0.91 | 0.90 | - |
| Linear Regression | ROI Estimation | - | - | 0.12 |
| ARIMA | Enrollment Forecasting | - | - | 0.08 |

## 🎥 Interactive Demo & Presentations

### 🌐 [**Live Interactive Presentation**](https://rosalinatorres888.github.io/ma-education-policy-analysis/)
Experience the full analysis with interactive visualizations, detailed findings, and policy recommendations through our GitHub Pages hosted presentation.

**Features:**
- Interactive data visualizations
- Comprehensive policy analysis walkthrough
- Key findings and recommendations
- Mobile-responsive design for accessibility

## 🔮 Future Work

- [ ] Implement deep learning models for complex pattern recognition
- [ ] Develop real-time dashboard with automated data updates
- [ ] Expand analysis to include neighboring states for comparative study
- [ ] Create API for programmatic access to insights
- [ ] Integrate NLP for policy document analysis
- [ ] Build recommendation engine for personalized intervention strategies

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss proposed modifications.

### Development Process
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📚 Citations & References

Key academic papers and government reports that informed this analysis:
- Heckman, J. J. (2006). "Skill Formation and the Economics of Investing in Disadvantaged Children"
- Massachusetts Department of Revenue (2024). "Fair Share Amendment Revenue Report"
- NAEP (2024). "The Nation's Report Card: State Assessments"

## 👤 Author

**Rosalina Torres**  
M.S. Data Analytics Engineering | Northeastern University  
Aspiring ML/AI Engineer | Education Policy Enthusiast

- 📧 Email: [torres.ros@northeastern.edu](mailto:torres.ros@northeastern.edu)
- 💼 LinkedIn: [linkedin.com/in/rosalina2](https://www.linkedin.com/in/rosalina2)
- 🐙 GitHub: [@rosalinatorres888](https://github.com/rosalinatorres888)
- 🌐 Live Project: [MA Education Policy Analysis](https://rosalinatorres888.github.io/ma-education-policy-analysis/)

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Massachusetts Department of Elementary and Secondary Education for data access
- Northeastern University faculty advisors for guidance
- Open-source community for analytical tools and frameworks

---

<p align="center">
<i>"Data illuminates the path; policy paves the way; education transforms the future."</i>
</p>

<p align="center">
Made with ❤️ and 📊 in Massachusetts
</p>
