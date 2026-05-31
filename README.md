# Quantium-Retail-Strategy-Analytics-
 This project is part of the Quantium Virtual Internship, focusing on data preparation and customer analytics for a large FMCG retailer.The goal is to analyze transaction and customer data to understand purchasing behavior, identify key customer segments, and provide actionable recommendations to the Category Manager to drive category growth.e 
# Quantium Retail Strategy & Analytics — Task 1
**Data Preparation & Customer Analytics**

## 📌 Overview
This project analyzes chip purchasing behavior for a major retailer, as part of the Quantium Data Analytics Virtual Internship. We clean transactional and customer data, perform segmentation, and deliver insights and recommendations for the Category Manager.

## 📊 Business Problem
We need to understand:
- Who buys chips, and how much they spend
- What they buy (brands, pack sizes)
- How behavior differs by customer segment
- Which segments drive the most revenue

## 📁 Data
**Sources**:
- `QVI_transaction_data.csv`: 264k+ transactions
- `QVI_purchase_behaviour.csv`: 72k+ customers

**Derived Features**:
- `PACK_SIZE`: Extracted weight in grams
- `BRAND`: Standardized brand name
- `PRICE_PER_UNIT`: Calculated price per pack

## 🛠️ Methodology
1. **Data Loading & Validation**: Check formats, missing values, ranges
2. **Cleaning**: Fix dates, remove non-chip products, filter outliers
3. **Feature Engineering**: Extract brand, pack size; standardize names
4. **Integration**: Merge transaction and customer datasets
5. **Exploratory Analysis**: Trends, volume, sales
6. **Segmentation**: Compare behavior by lifestage & premium status
7. **Statistical Testing**: Confirm significant differences
8. **Visualization & Insights**: Generate charts and recommendations

## 🚀 How to Run
1. Install required packages:
```r
install.packages(c("data.table", "ggplot2", "ggmosaic", "readr"))
