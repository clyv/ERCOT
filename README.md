# ERCOT Grid Analytics Dashboard 2024

## 🎯 **Comprehensive Analysis of Texas Electricity Grid Performance**

This repository contains an advanced analysis of the ERCOT (Electric Reliability Council of Texas) electricity grid, featuring interactive dashboards, statistical analysis, and economic insights covering both single-year (2024) and multi-year (2014-2024) perspectives.

## 📊 **View Notebooks Online**

### **Enhanced ERCOT Dashboard (2024 Analysis)**
[![View on GitHub](https://img.shields.io/badge/View%20on-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/clyv/ERCOT/blob/main/sbg2024.ipynb)
[![Open in NBViewer](https://img.shields.io/badge/Open%20in-NBViewer-orange?style=for-the-badge&logo=jupyter)](https://nbviewer.org/github/clyv/ERCOT/blob/main/sbg2024.ipynb)
[![Open in Colab](https://img.shields.io/badge/Open%20in-Colab-F9AB00?style=for-the-badge&logo=googlecolab)](https://colab.research.google.com/github/clyv/ERCOT/blob/main/sbg2024.ipynb)

### **🆕 Enhanced Multi-Year Analysis (2014-2024 Historical Trends)**
[![View on GitHub](https://img.shields.io/badge/View%20on-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/clyv/ERCOT/blob/main/sbgall_enhanced.ipynb)
[![Open in NBViewer](https://img.shields.io/badge/Open%20in-NBViewer-orange?style=for-the-badge&logo=jupyter)](https://nbviewer.org/github/clyv/ERCOT/blob/main/sbgall_enhanced.ipynb)
[![Open in Colab](https://img.shields.io/badge/Open%20in-Colab-F9AB00?style=for-the-badge&logo=googlecolab)](https://colab.research.google.com/github/clyv/ERCOT/blob/main/sbgall_enhanced.ipynb)

### **Multi-Year Analysis (2014-2024 Original)**
[![View on GitHub](https://img.shields.io/badge/View%20on-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/clyv/ERCOT/blob/main/sbgall.ipynb)
[![Open in NBViewer](https://img.shields.io/badge/Open%20in-NBViewer-orange?style=for-the-badge&logo=jupyter)](https://nbviewer.org/github/clyv/ERCOT/blob/main/sbgall.ipynb)
[![Open in Colab](https://img.shields.io/badge/Open%20in-Colab-F9AB00?style=for-the-badge&logo=googlecolab)](https://colab.research.google.com/github/clyv/ERCOT/blob/main/sbgall.ipynb)

## 🚀 **Dashboard Features**

### **🔥 NEW: Multi-Year Historical Analysis**
- 📈 **Decade Energy Evolution**: Interactive stacked area charts showing transformation from 2014-2024
- 🌱 **Renewable Revolution Tracking**: Dual-axis analysis of renewable energy growth and percentage
- 🔄 **Fuel Mix Transformation**: 100% stacked charts showing changing energy composition
- 📊 **Growth Rate Analysis**: Year-over-year growth calculations for all fuel types
- 🎯 **Data Quality Enhancement**: Robust data loading with standardized fuel categorization

### **Interactive Visualizations**
- 📈 **Multi-panel Plotly dashboards** with hover effects and zoom capabilities
- 🎨 **Professional styling** with consistent color schemes
- 📊 **Real-time data exploration** with interactive legends

### **Advanced Analytics**
- 🔍 **Statistical Analysis**: Correlation matrices, trend analysis, variability studies
- 💰 **Economic Insights**: Market price analysis and revenue projections
- ⚡ **Load Analysis**: Demand patterns and grid reliability metrics
- 🌱 **Sustainability Metrics**: Renewable energy penetration tracking

### **Key Insights**
- ✅ Renewable energy share and growth trends (historical perspective)
- ✅ Seasonal demand patterns and peak analysis
- ✅ Fuel mix optimization opportunities
- ✅ Market price volatility and economic impact
- ✅ Grid reliability and performance indicators
- ✅ **NEW**: Decade-long transformation patterns

## 📂 **Repository Contents**

| File | Description | Analysis Period | Size |
|------|-------------|----------------|------|
| `sbg2024.ipynb` | **Enhanced ERCOT Dashboard 2024** | 2024 only | Main analysis |
| `sbg2024_enhanced.ipynb` | Enhanced dashboard backup | 2024 only | Backup copy |
| `sbgall_enhanced.ipynb` | **🆕 Enhanced Multi-Year Analysis** | 2014-2024 | **Historical trends** |
| `sbgall.ipynb` | Multi-year analysis (original) | 2014-2024 | Original version |
| `IntGenbyFuel2024.xlsx` | 2024 generation data by fuel type | 2024 | 2.8 MB |
| `Native_Load_2024.xlsx` | 2024 regional load data | 2024 | 1.1 MB |
| `IntGenbyFuel*.xlsx` | Historical generation data | 2014-2020, 2022 | Various |

## 🎓 **Inspiration & References**

This dashboard was inspired by:
- [UT Austin Grid Analytics](https://grid-analytics.ece.utexas.edu/)
- [ERCOT Official Dashboards](https://www.ercot.com/gridmktinfo/dashboards)
- [IOP Science Grid Studies](https://iopscience.iop.org/article/10.1088/1748-9326/ab560d)

## 🛠 **Technical Stack**

- **Python 3.8+**
- **Jupyter Notebooks**
- **Plotly** (Interactive visualizations)
- **Pandas** (Data processing)
- **Matplotlib/Seaborn** (Statistical plots)
- **NumPy/SciPy** (Numerical analysis)

## 📋 **Quick Start**

1. **View online** using the badges above
2. **Clone repository**: `git clone https://github.com/clyv/ERCOT.git`
3. **Install dependencies**: `pip install pandas plotly matplotlib seaborn openpyxl`
4. **Run notebooks**: Open in Jupyter Lab/Notebook

## 📈 **Key Performance Indicators**

### **2024 Snapshot**
| Metric | 2024 Value |
|--------|------------|
| 🌱 Renewable Energy Share | ~30-40% |
| ⚡ Total Annual Generation | ~400,000 GWh |
| 🏆 Leading Energy Source | Natural Gas |
| 📊 Peak Generation Month | Summer months |
| 💚 Grid Reliability | HIGH (Diverse fuel mix) |

### **🆕 Historical Transformation (2014-2024)**
| Metric | Transformation |
|--------|----------------|
| 🌪️ Wind Energy Growth | **Massive expansion** (300%+ growth) |
| ☀️ Solar Energy Adoption | **Exponential growth** from near-zero |
| 🔥 Coal Dependency | **Dramatic decline** (retirement of plants) |
| ⚡ Natural Gas Role | **Continued dominance** as baseload |
| 🌱 Renewable Penetration | **15% → 35%+** over the decade |

## 🎯 **Analysis Objectives**

**Question**: Can we visualize key performance metrics for the ERCOT grid?

**Approach**:
1. **Get the data** ✅ - ERCOT hourly generation and load data
2. **Plot the data** ✅ - Interactive dashboards and statistical analysis
3. **Make a dashboard** ✅ - Comprehensive analytics platform

**Metrics Analyzed**:
- Electricity production by generator type (Wind, Solar, Natural Gas, Coal, Nuclear)
- Time period analysis (monthly, seasonal, annual, **decade-long trends**)
- Location-based analysis by ERCOT regions
- Market prices and economic impact
- Grid reliability and sustainability metrics
- **NEW**: Historical transformation patterns and renewable energy revolution

## 🌟 **What's New in Enhanced Multi-Year Analysis**

- 📊 **Comprehensive Historical Context**: Track the evolution of Texas grid over a full decade
- 🌱 **Renewable Energy Revolution**: Visualize the dramatic transformation from fossil-dominated to renewables
- 📈 **Advanced Growth Metrics**: Year-over-year percentage changes and trend analysis
- 🎨 **Enhanced Visualizations**: 4-panel interactive dashboards with professional styling
- 🔧 **Robust Data Processing**: Improved data loading with error handling and standardization
- 💡 **Policy Impact Analysis**: Understand how regulatory changes affected the energy landscape

---

*This project provides comprehensive insights into Texas electricity grid performance across both current operations (2024) and historical transformation (2014-2024), supporting data-driven decisions for energy planning and policy development.*