# 🏠 Ames Housing Data Analysis

Exploratory Data Analysis (EDA) on the Ames Housing dataset to identify key factors influencing house prices. This project focuses on data cleaning, feature analysis, correlation studies, and visualization to extract meaningful insights from real-world housing data.

---

## 🚀 Features

- Data cleaning and preprocessing (handling missing values, outliers)
- Univariate and multivariate analysis
- Correlation analysis to identify price-driving factors
- Visualizations using Matplotlib and Seaborn
- Insights into key variables affecting housing prices

## Project Structure

ames-housing-analysis/
│
├── images/
├── notebooks/
   -- analysis.ipynb
   -- data-wrangling-basic.ipynb   
├── Housing.csv
├── README.md
├── requirements.txt


## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---
## Key Findings

- OverallQual is strongly correlated with SalePrice.
- GrLivArea has a significant impact on housing prices.
- Newer houses generally sell at higher prices.

## Conclusion

The analysis identified several important factors influencing house prices. These insights can be used for future predictive modeling and feature engineering.



## 📦 Installation

Follow these steps to run the project locally:

```bash
# 1. Clone the repository
git clone https://github.com/Rupendra247/ames-housing-analysis.git

# 2. Navigate to the project folder
cd ames-housing-analysis

# 3. (Optional) Create a virtual environment
python -m venv venv

# 4. Activate the virtual environment
# On Windows:
venv\Scripts\activate
# On Mac/Linux:
source venv/bin/activate

# 5. Install required dependencies
pip install -r requirements.txt

Author Rupendra Dhungana
