# 🏭 Smart Inventory Optimization using Machine Learning

An intelligent inventory management system that leverages advanced machine learning algorithms to optimize stock control through ABC Classification methodology. This project addresses the critical challenges of modern supply chain management, particularly in volatile market conditions like those experienced during the COVID-19 pandemic.

## 🎯 Project Overview

This system implements a comprehensive ML-driven approach to inventory classification and optimization, helping businesses make data-driven decisions about stock levels, reorder points, and resource allocation. By applying the Pareto 80/20 principle through ABC Classification, the system categorizes inventory items based on their relative importance and value contribution.

## 🔬 Machine Learning Algorithms Implemented

The project compares and evaluates five powerful ML algorithms for inventory classification:

- **Random Forest Classifier** - *Best Performance: 93% accuracy*
- **Decision Tree Algorithm** - *87% accuracy*
- **Naïve Bayes Classifier** - *74% accuracy*
- **K-Nearest Neighbors (KNN)** - *54% accuracy*
- **Support Vector Machines (SVM)** - *40% accuracy*

## 🏗️ System Architecture

### Core Components:
1. **Data Preprocessing & Feature Selection** - Intelligent data preparation and feature engineering
2. **ML Algorithm Implementation** - Multiple classifier models for ABC categorization
3. **Database Management System** - Robust data storage and retrieval system
4. **Flask Web Interface** - User-friendly front-end for system interaction

### ABC Classification Framework:
- **Class A**: High-value, high-priority items (require aggressive management)
- **Class B**: Medium-value items (moderate management approach)
- **Class C**: Low-value items (efficient, cost-effective management)

## 📊 Key Features

- **Multi-Criteria Classification**: Considers factors like cost, demand patterns, seasonality, and supply chain dynamics
- **Real-time SKU Classification**: Dynamic categorization of stock-keeping units
- **Predictive Analytics**: Demand forecasting and inventory optimization
- **Performance Metrics**: Comprehensive evaluation using precision, recall, F1-score, and accuracy
- **Comparative Analysis**: Side-by-side comparison of multiple ML algorithms

## 🔧 Technology Stack

- **Backend**: Python
- **Machine Learning**: scikit-learn, pandas, numpy
- **Database**: SQL-based DBMS
- **Data Processing**: Feature engineering and preprocessing pipelines

## 📈 Dataset Features

The system analyzes inventory items based on 14 key parameters:
- Item Cost & Count
- Total Cost & Lead Time
- Shelf Life & EOQ (Economic Order Quantity)
- Lead Time Variability
- Seasonality Patterns
- Warehouse Location
- Customer Reviews
- Historical Sales Data
- Demand Fluctuation
- ABC Classification Labels

## 🎯 Business Impact

- **Cost Reduction**: Optimized inventory levels reduce carrying costs
- **Stockout Prevention**: Intelligent reorder point calculations
- **Resource Optimization**: Efficient allocation based on item importance
- **Supply Chain Resilience**: Better handling of demand volatility
- **Data-Driven Decisions**: ML-powered insights for strategic planning

## 🚀 Getting Started

### Prerequisites
```bash
Python 3.7+
Flask
scikit-learn
pandas
numpy
matplotlib
seaborn
```

### Installation
```bash
git clone https://github.com/JRK-007/Smart-Inventory-Optimization-ML.git
cd smart-inventory-optimization
pip install -r requirements.txt
```

### Usage
```bash
python app.py
```

## 📊 Performance Results

| Algorithm | Accuracy | Use Case |
|-----------|----------|----------|
| Random Forest | 93% | Best overall performance |
| Decision Tree | 87% | Interpretable decisions |
| Naïve Bayes | 74% | Fast processing |
| KNN | 54% | Pattern recognition |
| SVM | 40% | Complex boundaries |

## 🔍 Research Foundation

This project is based on comprehensive research in ML-driven inventory management, with particular focus on:
- ABC Classification methodology
- Multi-criteria decision making
- Supply chain optimization
- Pandemic-resilient inventory systems

### 📄 Base Paper Citation

This implementation is based on the research paper:

**Bailkar, S., Bankar, S., Shenoy, K., More, P., & Bedekar, A.** (2024). Smart Inventory Optimization using Machine Learning Algorithms. In *Proceedings of the 2nd International Conference on Intelligent Data Communication Technologies and Internet of Things (IDCIoT-2024)* (pp. 1395-1400). IEEE. https://doi.org/10.1109/IDCIOT59759.2024.10467512

**Abstract:** Industries increasingly rely on efficient inventory management, logistics, and supply chain operations, and ML-based intelligence frameworks have emerged as indispensable tools. This research centers around the application of ML techniques within the framework of the ABC Inventory Classification methodology, examining five ML algorithms: Decision Tree Algorithm, Support Vector Machines (SVM), Random Forest Classifier, Naïve Bayes Classifier and K-nearest neighbors (KNN), with Random Forest Classifiers achieving the highest accuracy at 93%.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Primary Research**: Based on the IEEE conference paper "Smart Inventory Optimization using Machine Learning Algorithms" by Bailkar et al. (2024)
- **Institution**: School of Technology Management & Engineering, SVKM's NMIMS University, Navi Mumbai, Maharashtra
- **Research Team**: Shreyas Bailkar, Sandip Bankar, Kunal Shenoy, Pranav More, Amogh Bedekar
- Supply chain management best practices and methodologies
- ABC Classification framework and Pareto principle applications

### 📚 Additional References
For comprehensive understanding of the theoretical foundation, refer to the complete list of references in the base paper, including works on:
- Business Intelligence solutions during COVID-19 pandemic
- IoT and machine learning based inventory systems
- Economic Order Quantity (EOQ) and Just-In-Time (JIT) methodologies
- Support Vector Machines and Decision Tree applications in supply chain management

## 📞 Contact

For questions or collaboration opportunities, please reach out:

📧 **Email**: [tomyblog007@gmail.com]
🐙 **GitHub**: [[@JRK-007](https://github.com/JRK-007)]
💼 **LinkedIn**: [[LinkedIn Profile](https://www.linkedin.com/in/rahul-krishna-j/)]

Feel free to open GitHub issues for bug reports, feature requests, or general discussions about the project.

---

*Making inventory management intelligent, one algorithm at a time* 🤖📦
