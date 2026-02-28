# Google Play Store - Exploratory Data Analysis (EDA)

**Author: Megha Kallapur**  
 Bengaluru, India | meghakallapur22@gmail.com | GitHub : https://github.com/Megha-B-K

# Google Play Store App Analysis - EDA

**Location**: Karnataka, India  
**[GitHub](https://github.com/Megha-B-K)** | **[LinkedIn](https://linkedin.com/in/meghakallapur)**

---

## Project Overview

Comprehensive **Exploratory Data Analysis** of **10,841 Google Play Store apps** to uncover success patterns, category trends, and pricing strategies.

**Dataset**: Real Google Play Store data with app ratings, installs, sizes, categories, and pricing.

**Business Questions**:
- Which categories dominate downloads?
- Rating vs Installs correlation?
- Free vs Paid app performance?
- Size impact on popularity?

---

## Dataset Overview (10,841 Apps)

| Feature | Description | Key Stats |
|---------|-------------|-----------|
| **Category** | App category | FAMILY (1,832), GAME (959) |
| **Rating** | User rating (1-5) | Avg: 4.19  |
| **Reviews** | User reviews count | 159 → 398K+ |
| **Installs** | Download count | 1K+ → 50M+ |
| **Size** | App size | 2.8MB → 25MB avg |
| **Price** | Free/Paid | 99.9% Free apps |
| **Content Rating** | Age restrictions | Everyone (most common) |

---

##  EDA Analysis Performed

### Data Cleaning Pipeline
```python
# From your notebook[1]
- Removed 1 bad row (10472: "Life Made WI-Fi...")
- Fixed Size: "19M" → 19000 KB
- Fixed Installs: "10,000+" → 10000
- Fixed Price: "$0.99" → 0.99
- Handled NaN Ratings (1,474 rows)
- Date parsing for Last Updated

## Key Visualizations Created
Category distribution (FAMILY/GAME dominate)

Rating vs Installs scatter plot

Price analysis (Free vs Paid)

Size vs Popularity correlation

Content Rating trends

Review count histograms

## Key Business Insights
FAMILY category leads with 1,832 apps (17%)

Average rating 4.19- most apps well-received

Free apps = 99.9% market share

High installs correlate with 4.0+ ratings

Smaller apps (<10MB) get more downloads

GAME apps have highest review volume

Gmail: meghakallapur@gmail.com
Last Updated: February 2026
