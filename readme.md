# 📊 Customer Purchasing Behavior & Sales Optimization in Electronics Market

## 📌 Project Overview
This project analyzes customer purchasing behavior and sales optimization strategies in the electronics market. Using transaction data from September 2023 to September 2024, the analysis provides insights such as sales trends, customer demographics, order cancellations, correlations between key variables, and customer segmentation using RFM analysis to help improve business strategies.

## 🛠 Technical Specifications
- **Languages**: Python
- **Key Libraries**: 
  - Data Analysis: Pandas
  - Visualization: Matplotlib, Seaborn
  - Machine Learning: Scikit-learn
- **Analytical Techniques**: 
  - RFM Segmentation
  - Correlation Heatmaps
  - Time-Series Decomposition
- **Data Source**: Kaggle Electronics Sales Dataset

## 🛠️ Methods & Analysis
this project uses the following methods to generate insight:
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Visualizations using Seaborn, Matplotlib, and Plotly
- Sales Performance Trends
- Order Cancellation Analysis
- Correlation Analysis between key features
- Customer Segmentation using RFM (Recency, Frequency, Monetary)

 ## 📈 Key Insights
 ### 🛒 Product & Sales Trends
 -  Smartphones are the most purchased product category, followed by tablets and laptops.
 -  Expensive products sell less frequently than cheaper ones, but their ratings vary without a consistent trend.
 -  Sales increased significantly at the beginning of 2024, particularly around the New Year. In the following months, sales became more stable and consistent.

### 👥 Customer Behavior
- The 35–64 age group contributes the most to total sales.
- The majority of customers are non-loyal (78%), yet the average spend between loyal and non-loyal customers is nearly the same
- Credit card and PayPal are the most commonly used payment methods by customers.
- Male and female customers are almost equal in number and show similar product preferences.

### ❌ Order Cancellation
- In general, the ratio of completed to canceled orders is approximately 67:33.
- SKUs with higher-priced products tend to have a higher order completion rate.
- There was a significant spike in order cancellations by payment method during the New Year of 2024, particularly among Credit Card, PayPal, and Bank Transfer users.



## 📂 Project Structure
```
📦 electronics-sales-analysis
├── 📂 data
│   ├── raw.csv               # Original dataset
│   └── cleaned.csv           # Processed data
├── 📂 notebooks
│   └── analysis.ipynb        # Comprehensive analysis notebook
├── 📂 reports
│   ├── sales_trend.png       # Quarterly sales visualization
│   └── rfm_heatmap.png       # Customer segment matrix
└── README.md
```

## 🚀 Setup & Installation
1. Clone the repository:
```bash
git clone https://github.com/yourname/electronics-sales-analysis.git
cd electronics-sales-analysis
```

2. Create virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Unix or MacOS
# venv\Scripts\activate   # On Windows
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Run the Jupyter Notebook:
```bash
jupyter notebook notebooks/analysis.ipynb
```

## 🔍 Future Research Directions
- **Predictive Modeling**: 
  - Demand forecasting using ARIMA models
- **Experimental Analysis**:
  - A/B testing of promotional strategies for RFM segments
- **Machine Learning Expansion**:
  - Develop customer churn prediction model
  - Create recommendation system based on purchasing patterns

## 🤝 Contribution & Collaboration
- Open to collaborations and improvements
- Please submit issues or pull requests on GitHub
- Feedback and suggestions are welcome!

## 📞 Contact
- **Email**: [your.email@example.com]
- **LinkedIn**: [Your LinkedIn Profile]

## ✨ Key Insights
**⭐ Critical Takeaway**: Urban millennials represent the highest-value customer segment. By addressing logistics bottlenecks and implementing targeted marketing strategies, the potential revenue boost could reach 15-20%.

## 📝 Notes
- All visualizations are reproducible via the Jupyter notebook
- Ensure dataset is placed in `/data` directory before execution
- Detailed methodology available in the analysis notebook

## 📜 License
[Choose an appropriate open-source license, e.g., MIT, Apache 2.0]
