# Retail Sales Data Analysis with AI-Assisted Customer Segmentation

**AICTE | IBM SkillsBuild Data Analytics with AI Internship 2026**

**Candidate:** Manish Singh Bisht

## Project Description

This project performs exploratory data analysis on retail transaction data and uses a simple K-Means clustering model to segment customers according to their purchasing behavior.

The project covers:
- Data loading and validation
- Missing-value and duplicate checks
- Data cleaning and feature engineering
- Revenue and transaction KPIs
- Product-category analysis
- Monthly sales trends
- Gender and age-group analysis
- Customer segmentation using K-Means
- Data visualization
- Business recommendations

## Dataset

The dataset is a public retail sales dataset containing transaction ID, date, customer ID, gender, age, product category, quantity, price per unit, and total amount.

**Dataset source:**  
https://github.com/Seunfunmee/Retail-Sales-Data-Set

The source repository states that the dataset contains 1,000 retail transactions and is originally sourced from Kaggle.

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## AI/ML Component

K-Means clustering is used as the AI/ML component. Customers are grouped using:
- Total spending
- Number of transactions
- Total quantity purchased
- Average transaction value

This helps demonstrate how unsupervised machine learning can support customer segmentation.

## Project Structure

```text
ManishSinghBisht_RetailSalesAnalysis.ipynb
requirements.txt
ManishSinghBisht_ProjectReport.docx
README.md
```

## Setup Instructions

1. Install Python 3.9 or later.
2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Open the notebook:

```bash
jupyter notebook
```

4. Run `ManishSinghBisht_RetailSalesAnalysis.ipynb` from top to bottom.

The notebook first attempts to load the dataset from the public GitHub source. If that is unavailable, download `Retail Sales Data Set.csv` from the dataset repository and place it in the same folder as the notebook.

## Expected Output

The notebook generates:
- Dataset quality checks
- Revenue KPIs
- Category revenue charts
- Monthly revenue trend
- Gender and age-group analysis
- Customer clusters
- Correlation heatmap
- Business recommendations

## Note

This project is for academic and educational purposes. The dataset is publicly available and should be treated as sample retail data rather than confidential business information.
