# 🌾 Agriculture Market Analyzer

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Processing-green)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-orange)

Interactive Python-based analytics tool for agricultural commodity market analysis across Indian states. Processes 10,000+ market records to deliver insights on pricing patterns, volatility, and regional variations.

---

## 🎯 Features

### 1. **Market-wise Price Distribution**
- Animated horizontal bar charts showing top 10 markets by price
- Interactive commodity selection from 15+ options
- State and market breakdown with price comparisons

### 2. **Price Heatmap**
- 2D visualization of prices across markets and commodities
- Top 8 commodities × Top 12 markets analysis
- Color-coded for quick pattern recognition

### 3. **Outlier Detection**
- Statistical outlier identification using IQR method
- Boxplot with strip plot overlay
- Percentage of outliers reported

### 4. **Volatility Analysis**
- Coefficient of Variation (CV) calculation
- Top 10 most volatile commodities ranked
- Risk assessment for procurement planning

### 5. **K-Means Clustering**
- Unsupervised learning for commodity segmentation
- Groups commodities by price and volatility patterns
- 2D scatter plot visualization

### 6. **Price Stability Index**
- Custom stability metric for consistent pricing
- Top 10 most stable commodities
- Useful for long-term contracts

---

## 🛠️ Tech Stack

- **Python 3.8+**
- **Pandas** - Data processing and aggregation
- **NumPy** - Numerical computations
- **Matplotlib** - Animated visualizations
- **Seaborn** - Statistical plots
- **Scikit-learn** - K-Means clustering and scaling

---

## 📊 Dataset

**Source**: Agricultural commodity market data across Indian states

**Key Fields**:
- Commodity name
- Market/Mandi location
- State
- Modal Price (most frequent price)
- Min/Max prices

**Volume**: 10,000+ records | 50+ commodities | 100+ markets

---

## 🚀 Installation & Usage

### Install Dependencies
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Run the Analyzer
```bash
python agriculture_market_analyzer.py
```

### Workflow
1. Enter CSV file path (or use default)
2. Select analysis type from menu (1-6)
3. Choose commodity for specific analyses
4. View interactive visualizations

---

## 💡 Key Insights

- Identified 30-40% price variations across states for identical commodities
- Perishable goods show 2-3x higher volatility than staples
- Discovered 4 distinct commodity clusters based on pricing patterns
- Flagged 5-8% of records as statistical outliers

---

## 🎓 Skills Demonstrated

**Data Science**: EDA, statistical analysis, feature engineering  
**Machine Learning**: K-Means clustering, StandardScaler  
**Visualization**: Animated charts, heatmaps, boxplots  
**Python**: OOP, error handling, data cleaning  

---

## 📁 Project Structure
```
agriculture-market-analyzer/
├── agriculture_market_analyzer.py  # Main analysis tool
└── README.md                       # Documentation
```

---

## 🔗 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ankit%20Kailey-blue)](https://linkedin.com/in/ankit-kailey)
[![GitHub](https://img.shields.io/badge/GitHub-ankitkailey18-black)](https://github.com/ankitkailey18)

---

## 📄 License

MIT License - Open source and free to use

---

**⭐ Star this repo if you found it helpful!**
