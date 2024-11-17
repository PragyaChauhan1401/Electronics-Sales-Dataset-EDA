# Electronics Sales Data Analysis

## Project Overview
This repository contains an analysis of electronics sales data spanning multiple states in the US. The dataset includes detailed transaction records with temporal, spatial, and product-specific information, providing insights into consumer purchasing patterns and retail performance.

## Dataset Description
The dataset consists of 185,950 records with 16 columns, covering various aspects of electronics sales transactions.

### Data Structure
```
Total Records: 185,950
Memory Usage: 22.0+ MB
Data Types: datetime64[ns](1), float64(2), int32(3), object(10)
```

### Columns
1. **Order ID**: Unique identifier for each transaction
2. **Product**: Name of the product sold
3. **Quantity Ordered**: Number of units purchased (int32)
4. **Price Each**: Unit price of the product (float64)
5. **Purchase Address**: Complete delivery address
6. **Date**: Transaction date (datetime64[ns])
7. **Time**: Transaction time
8. **Total Sale**: Total transaction amount (float64)
9. **Month**: Month of transaction
10. **Month_num**: Numerical representation of month
11. **Hour**: Hour of transaction (int32)
12. **City**: City where transaction occurred
13. **State**: State abbreviation
14. **State_name**: Full state name
15. **Minutes**: Minutes of transaction (int32)
16. **Day_of_week**: Day of the week

## Key Features
- Complete transaction history with temporal analysis capabilities
- Geographical data spanning multiple states
- Product-level sales information
- Derived metrics for enhanced analysis

## Analysis Highlights
- Seasonal sales patterns identification
- Product performance analysis
- Geographical sales distribution
- Time-based purchasing patterns
- Customer behavior insights

## Requirements
- Python 3.x
- Pandas
- Numpy
- Matplotlib
- Seaborn

## Installation
```bash
git clone https://github.com/yourusername/electronics-sales-analysis.git
cd electronics-sales-analysis
pip install -r requirements.txt
```

## Usage
```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

# Load the dataset
df = pd.read_csv('electronics_sales.csv')

# Basic data exploration
print(df.info())
print(df.describe())
```

## Visualizations
The repository includes various visualizations:
- Monthly sales trends
- Product-wise revenue contribution
- Geographical sales distribution
- Hourly sales patterns
- Day-of-week analysis

