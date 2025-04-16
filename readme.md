# 📊 Customer Purchasing Behavior & Sales Optimization in Electronics Market

## 📌 Project Overview
This project analyzes customer purchasing behavior and sales optimization strategies in the electronics market. Using transaction data from September 2023 to September 2024, the analysis provides insights such as sales trends, customer demographics, order cancellations, correlations between key variables, and customer segmentation using RFM analysis to help improve business strategies.

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

### 📊 RFM-Based Customer Segmentation
- Cluster 0 represents 'High-Value Customers' who shop relatively recently, make purchases most frequently, and spend significantly more money than other groups – these are your loyal customers who contribute substantially to revenue.
- Cluster 1 represents recent 'lower-value customers' consists of customers who have shopped most recently but make fewer purchases with moderate spending amounts, suggesting they might be newer customers or occasional shoppers with growth potential.
- Cluster 2 represents 'At-Risk Customers' shows concerning characteristics of inactive clients who haven't made purchases in a long time (about 251 days), rarely shop with you, and spend less when they do – these customers have likely churned or are at high risk of abandoning your business altogether

## 📊 Sales Optimization Strategy

### 🔍 Product Strategy
- 📱 Smartphone Focus: Maintain premium position with targeted advertising for the most purchased product category
- 💰 Price-Tier Segmentation: Develop clear value propositions for each price tier, as expensive products have higher completion rates
- 🔄 Product Bundling: Create smartphone + headphone/accessory bundles to leverage main product popularity
- 🎯 Seasonal Campaign Planning: Intensify marketing efforts before New Year to capitalize on demonstrated sales spike periods
 
### 👥 Customer-Centric Approach
- 👨‍👩‍👧‍👦 Age-Based Targeting: Focus primary campaigns on 35-64 age group while developing strategies to attract younger demographics
- ❤️ Loyalty Program Enhancement: Implement stronger incentives to convert the 78% non-loyal customers into repeat buyers
- 👫 Gender-Neutral Marketing: Maintain balanced marketing approach as male/female customers show similar preferences
- 💳 Payment Optimization: Optimize checkout experience for credit card and PayPal users while addressing New Year cancellation issues

### 🚀 Growth Initiatives
- 🏆 High-Value Customer Retention: Develop exclusive benefits for Cluster 0 ("High-Value Customers") to maintain loyalty
- 🌱 New Customer Nurturing: Create specialized onboarding and second-purchase incentives for Cluster 1 ("Lower-Value Customers")
- 🔁 Re-engagement Campaign: Implement targeted win-back strategy for Cluster 2 ("At-Risk Customers") with 251+ days of inactivity
- 📉 Cancellation Reduction: Address payment-related cancellations, especially during holiday season spikes

### 📈 Performance Monitoring
- 🔄 Completion Rate Tracking: Monitor order completion rates across product categories with goal to improve beyond 67:33 ratio
- 💵 Average Order Value: Increase AOV through strategic upselling based on customer segment behavior
- 📱 Category Expansion: Evaluate performance of lower-volume categories (headphones, smartwatches) for growth opportunities
- 🔍 Seasonal Variation Analysis: Implement adaptable marketing budget allocation based on identified seasonal trends
  
## 📂 Project Structure
```
📦 electronics-sales-analysis
├── 📂 Dataset
│   └── Electronic_sales.csv  # Original dataset
│   └── data_sales_electronic # Dataset after analysis
├── 📂 Notebooks
│   └── analysis.ipynb        # Comprehensive analysis notebook
├── 📂 Dashboard
│   └── sales_trend.png       # Quarterly sales visualization
│   └── Dashbboard.txt        # Link Full Dashboard
└── README.md
```

## 🚀 Setup & Installation
1. Clone the repository:
```bash
git clone https://github.com/JaysyuMuhammad/Customer-Purchasing-Behavior-and-Sales-Optimization-in-Electronics-Market.git
cd Customer-Purchasing-Behavior-and-Sales-Optimization-in-Electronics-Market
```

2. Create virtual environment (recommended):
```bash
# Windows
python -m venv venv
venv\Scripts\activate

# macOS/Linux
python3 -m venv venv
source venv/bin/activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Run the Jupyter Notebook:
```bash
jupyter notebook notebooks/analysis.ipynb
```



## 🤝 Contribution & Collaboration
- Open to collaborations and improvements
- Please submit issues or pull requests on GitHub
- Feedback and suggestions are welcome!

## 📞 Contact
- **Email**: muhammadjaysyu@gmail.com
- **LinkedIn**: www.linkedin.com/in/jaysyu-muhammad


