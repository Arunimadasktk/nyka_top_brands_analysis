# 🛍️ Nykaa Cosmetics Product Reviews - Complete Analytics Project

## 📋 Project Overview

This comprehensive analytics project provides end-to-end analysis of Nykaa cosmetics product reviews, including data cleaning, preprocessing, exploratory data analysis (EDA), and interactive Power BI dashboard creation.

### 🎯 Business Objectives
- Analyze customer satisfaction trends and patterns
- Identify top-performing brands and products
- Understand pricing strategies and discount impacts
- Discover customer behavior insights
- Create actionable business recommendations

### 📊 Project Components
1. **Data Analysis Pipeline** (Python/Jupyter)
2. **Interactive Dashboard** (Power BI)
3. **Business Insights** (Strategic Recommendations)
4. **Documentation** (Complete guides and instructions)

## 📁 Project Structure

### 📓 Jupyter Notebooks
- **data_cleaning.ipynb** - Data cleaning: missing values, duplicates, data type conversions, outlier detection
- **data_preprocessing.ipynb** - Preprocessing: feature engineering, text processing, encoding, transformations
- **eda.ipynb** - Exploratory data analysis with comprehensive visualizations

### 📊 Power BI Dashboard
- **Power BI Screenshots** - Dashboard visualizations (4 screenshots included)
- **POWER_BI_GUIDE.md** - Complete step-by-step Power BI implementation guide

### 📈 Data Files
- **nyka_top_brands_cosmetics_product_reviews.csv** - Original dataset
- **cleaned_data.csv** - Cleaned dataset ready for analysis
- **preprocessed_data.csv** - Preprocessed dataset with engineered features

### 📋 Documentation
- **README.md** - Project overview and instructions (this file)
- **KEY_INSIGHTS.md** - Business insights and strategic recommendations
- **POWER_BI_GUIDE.md** - Complete Power BI dashboard creation guide
- **requirements.txt** - Required Python packages

## 🚀 Quick Start Guide

### Option 1: Python Analysis Only

#### 1. Install Dependencies
```bash
pip install -r requirements.txt
```

#### 2. Launch Jupyter Notebook
```bash
jupyter notebook
```

#### 3. Run Notebooks in Sequence
1. **data_cleaning.ipynb** - Clean the raw data
2. **data_preprocessing.ipynb** - Preprocess and engineer features  
3. **eda.ipynb** - Perform exploratory data analysis

### Option 2: Complete Project (Python + Power BI)

#### 1. Complete Python Analysis (Steps 1-3 above)

#### 2. Create Power BI Dashboard
1. Install **Power BI Desktop**
2. Follow the **POWER_BI_GUIDE.md** for step-by-step instructions
3. Use `cleaned_data.csv` as your data source
4. Implement the dashboard as shown in the screenshots

#### 3. Review Business Insights
- Read **KEY_INSIGHTS.md** for strategic recommendations
- Use insights to drive business decisions

## 📊 What Each Notebook Does

### Data Cleaning (`data_cleaning.ipynb`)

- **Missing Values Analysis**: Identifies and reports missing data
- **Duplicate Detection**: Finds duplicate rows and review IDs
- **Text Cleaning**: Removes extra whitespaces and standardizes text
- **Numeric Conversion**: Converts ratings, prices to proper numeric types
- **Boolean Conversion**: Standardizes True/False values
- **Date Parsing**: Converts date strings to datetime objects
- **Outlier Removal**: Removes invalid ratings and negative prices
- **Output**: `cleaned_data.csv`

### Data Preprocessing (`data_preprocessing.ipynb`)

- **Feature Engineering**:
  - Date features (year, month, day, quarter, day of week)
  - Price features (discount, discount percentage)
  - Text features (length, word count)
  - Rating difference between review and product
  - Sentiment categories (Positive/Neutral/Negative)

- **Text Processing**:
  - Lowercasing
  - Special character removal
  - Tokenization
  - Stopword removal
  - Lemmatization

- **Encoding**:
  - Label encoding for brands
  - One-hot encoding for sentiment
  - Boolean encoding

- **Missing Value Handling**: Fills missing values with median/mode
- **Output**: `preprocessed_data.csv`

### Exploratory Data Analysis (`eda.ipynb`)

Generates comprehensive insights and visualizations:

#### Analyses Performed:
1. **Basic Statistics**: Dataset overview, unique counts, summary statistics
2. **Rating Analysis**: Distribution of ratings, mean/median ratings
3. **Brand Analysis**: Top brands by review count and average rating
4. **Price Analysis**: Price distributions, discount patterns
5. **Temporal Analysis**: Review trends over time
6. **Text Analysis**: Review length patterns, word count by rating
7. **Buyer Status**: Verified vs non-verified buyer patterns
8. **Correlation Analysis**: Relationships between numeric variables
9. **Word Cloud**: Most common words in reviews

#### Visualizations Generated:
- `review_rating_distribution.png` - Bar chart of rating distribution
- `top_brands.png` - Top 10 brands by review count
- `price_analysis.png` - Price and discount distributions
- `reviews_over_time.png` - Temporal trends
- `wordcount_by_rating.png` - Box plot of word count by rating
- `verified_buyer_distribution.png` - Pie chart of buyer status
- `correlation_matrix.png` - Heatmap of correlations
- `wordcloud.png` - Word cloud of review text

## 📈 Key Insights You'll Get

- **Rating Patterns**: How customers rate products
- **Brand Performance**: Which brands get most reviews and best ratings
- **Pricing Strategy**: Discount patterns and price distributions
- **Review Trends**: How review volume changes over time
- **Customer Behavior**: Verified vs non-verified buyer patterns
- **Text Patterns**: What customers write about in reviews
- **Correlations**: Relationships between different variables

## 🔧 Customization

You can modify the notebooks to:
- Add more feature engineering steps
- Change visualization styles
- Apply different text preprocessing techniques
- Add sentiment analysis models
- Implement additional statistical tests

## 📝 Notes

- The notebooks are interactive and allow you to explore the data step by step
- NLTK data (punkt, stopwords, wordnet) will be downloaded automatically if not present
- All visualizations are saved as high-resolution PNG files (300 DPI)
- Each notebook includes detailed markdown explanations and comments
- You can run cells individually or all at once

## 🐛 Troubleshooting

If you encounter issues:

1. **Jupyter Not Installed**: Install with `pip install jupyter` or `pip install notebook`
2. **NLTK Download Errors**: The notebooks will attempt to download required NLTK data automatically
3. **Memory Issues**: For large datasets, consider processing in chunks or restart the kernel
4. **Missing Packages**: Ensure all requirements are installed: `pip install -r requirements.txt`
5. **Kernel Issues**: Try restarting the kernel from the Jupyter menu

## 📊 Project Deliverables

### 📈 Python Analysis Outputs
- **cleaned_data.csv** - Cleaned dataset ready for analysis
- **preprocessed_data.csv** - Feature-engineered dataset
- **8 Visualization PNG files**:
  - review_rating_distribution.png
  - top_brands.png  
  - price_analysis.png
  - reviews_over_time.png
  - wordcount_by_rating.png
  - verified_buyer_distribution.png
  - correlation_matrix.png
  - wordcloud.png

### 📊 Power BI Dashboard
- **Interactive Dashboard** with 4 main pages:
  - Executive Summary
  - Brand Performance Analysis
  - Customer Insights
  - Product & Pricing Analysis
- **Screenshots** showing implemented visualizations
- **Complete implementation guide**

### 📋 Business Intelligence
- **Key Insights Report** with actionable recommendations
- **Strategic analysis** of customer behavior patterns
- **Performance metrics** and KPIs
- **Future opportunities** and market trends

## 🎯 Key Features

### 🔍 Advanced Analytics
- **Sentiment Analysis** of customer reviews
- **Time Series Analysis** of review trends
- **Price Optimization** insights
- **Brand Performance** benchmarking
- **Customer Segmentation** analysis

### 📊 Interactive Visualizations
- **Power BI Dashboard** with drill-down capabilities
- **Python Visualizations** with statistical insights
- **Mobile-responsive** design
- **Real-time filtering** and slicing

### 🚀 Business Value
- **Data-driven decision making** capabilities
- **Customer satisfaction** optimization
- **Revenue growth** opportunities
- **Market positioning** insights
- **Competitive analysis** framework

## 💡 Usage Tips

### For Jupyter Notebooks
- Run cells sequentially from top to bottom
- Use `Shift + Enter` to run a cell and move to the next
- Use `Ctrl + Enter` to run a cell and stay on it
- Modify code cells to explore additional insights
- Add your own analysis cells as needed

### For Power BI Dashboard
- Follow the **POWER_BI_GUIDE.md** step-by-step
- Use the provided DAX formulas for calculations
- Customize colors and themes to match brand guidelines
- Test interactivity and drill-through functionality
- Publish to Power BI Service for sharing

## 🎉 Project Highlights

✅ **Complete end-to-end analytics pipeline**  
✅ **Professional Power BI dashboard**  
✅ **Actionable business insights**  
✅ **Comprehensive documentation**  
✅ **Reproducible analysis workflow**  
✅ **Industry best practices**  

**Ready to transform your data into business value!** 🚀
