# 🛍️ Mall Customer Visits Prediction

## 📖 Project Description
This machine learning project predicts which days of the week customers are most likely to revisit a shopping mall. Using historical visit patterns, we've developed a multiclass classification system that forecasts specific weekdays when customers will return.

**Team**: Group 2 - GDSC UIN Jakarta Study Jams  
**Project Type**: Multiclass Classification  
**Domain**: Retail Analytics, Customer Behavior Prediction

---

## 🎯 Business Objective
Help mall management optimize operations by predicting customer footfall patterns, enabling better:
- Staff scheduling
- Promotional planning  
- Resource allocation
- Customer experience enhancement

---

## 📊 Dataset Overview

### Source & Structure
- **Source**: Historical customer visit records
- **Format**: CSV files (`train_set.csv`, `test_set.csv`)
- **Records**: 99 unique customers with 3,229 total visits

### Features
| Feature | Description | Type |
|---------|-------------|------|
| `visitor_id` | Unique customer identifier | Integer |
| `visits` | Sequence of visit days (space-separated) | String |
| `visit_day` | Individual visit day number | Integer |
| `day_of_week` | Derived day of week (1-7) | Integer |
| `week_number` | Week sequence number | Integer |
| `month_position` | Approximate month position | Integer |

---

## 🛠️ Technical Implementation

### Libraries & Tools
```python
# Core Data Science
pandas, numpy, scipy

# Machine Learning
scikit-learn, LogisticRegression

# Visualization
plotly, seaborn

# Utilities
gdown, pickle, warnings
