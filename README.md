# Google Play Store - Exploratory Data Analysis (EDA)

**Author: Megha Kallapur**  
 Bengaluru, India | meghakallapur22@gmail.com 

## Overview
Comprehensive EDA on **Google Play Store dataset** with **10,000+ apps** to analyze app performance, category trends, rating patterns, and pricing strategies. Classic data analytics project used worldwide for portfolio building.

**Key Insights:**
- Top performing app categories by installs/ratings
- Rating vs Reviews/Installs correlation analysis
- Free vs Paid app performance
- Content rating impact on popularity

## Dataset
- **Source**: `googleplaystore.csv` (12+ columns: App, Category, Rating, Reviews, Size, Installs, Type, Price, Content_Rating, etc.)
- **Size**: 10,000+ app records
- **Challenges**: Missing ratings (~13%), inconsistent installs ("1,000+", "+"), data type issues
- **Features Analyzed**: Category distributions, rating histograms, installs segmentation

## Tech Stack
- **Languages/Tools**: Python, Pandas, NumPy, Matplotlib, Seaborn
- **Environment**: Jupyter Notebook

## EDA Process
1. **Data Loading & Inspection**: CSV import, shape analysis, data types, null checks
2. **Data Cleaning**: 
   - Handled missing ratings (~13%)
   - Cleaned installs ("1,000+" → numeric)
   - Price conversion ("$0.99" → float)
   - Size standardization ("1.2M" → MB)
3. **Feature Engineering**:
   - Installs categorization (Low/Medium/High)
   - Price tiers (Free/Paid)
   - Category grouping
4. **Analysis**:
   - Category-wise rating/installs comparison
   - Rating distribution & outliers
   - Correlation analysis (Reviews vs Rating)
   - Top apps visualization
5. **Business Insights**: Best categories for app development, pricing strategies

## Skills Demonstrated
- Large-scale categorical data analysis
- Missing data imputation strategies
- Text data cleaning (installs, price, size)
- Statistical distributions & correlations
- Business metric analysis (ratings, installs)
- Multi-dimensional visualization
