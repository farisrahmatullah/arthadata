# Enhancing Marketing Campaign Efficiency with Predictive Analysis - Artha Data
Final Project - Data Science by Rakamin Batch 45 Kelompok 1

## Project Overview

This project aims to analyze a marketing campaign dataset to gain insights into customer behavior, preferences, and responses to various marketing strategies. By leveraging data science techniques, we can provide actionable recommendations to improve future marketing efforts and enhance customer engagement. A key component of this project is to predict whether a user will respond to the next campaign. To achieve this, we will employ classification algorithms to model user responses based on historical data. The classification models will help identify patterns and factors influencing user engagement, enabling targeted and effective marketing strategies.

## Authors
 
- [Yoga Aprila](link)
- [Zaima Syarifa Asshafa](link)
- [Muhammad Fauzi Fayyad](link)
- [Faris Rahmatullah](link)
- [Deni Yuniawan](link)
- [Rafa Kamila](link)
- [Nijma Fuaiyida Hanum](link)

## Dataset

The dataset, sourced from Kaggle, contains information on customer demographics, purchase history, and responses to marketing campaigns. Key attributes include:

- **ID**: Unique identifier for each customer.
- **Year_Birth**: Year of birth of the customer.
- **Education**: Educational background of the customer.
- **Marital_Status**: Marital status of the customer.
- **Income**: Annual income of the customer.
- **Kidhome**: Number of small children at home.
- **Teenhome**: Number of teenagers at home.
- **Dt_Customer**: Date of customer enrollment with the company.
- **Recency**: Number of days since the last purchase.
- **MntWines**: Amount spent on wine in the last 2 years.
- **MntFruits**: Amount spent on fruits in the last 2 years.
- **MntMeatProducts**: Amount spent on meat products in the last 2 years.
- **MntFishProducts**: Amount spent on fish products in the last 2 years.
- **MntSweetProducts**: Amount spent on sweets in the last 2 years.
- **MntGoldProds**: Amount spent on gold products in the last 2 years.
- **NumDealsPurchases**: Number of purchases made with a discount.
- **NumWebPurchases**: Number of purchases made through the company’s website.
- **NumCatalogPurchases**: Number of purchases made using a catalog.
- **NumStorePurchases**: Number of purchases made directly in stores.
- **NumWebVisitsMonth**: Number of visits to the company’s website in the last month.
- **AcceptedCmp1**: 1 if the customer accepted the offer in the 1st campaign, 0 otherwise.
- **AcceptedCmp2**: 1 if the customer accepted the offer in the 2nd campaign, 0 otherwise.
- **AcceptedCmp3**: 1 if the customer accepted the offer in the 3rd campaign, 0 otherwise.
- **AcceptedCmp4**: 1 if the customer accepted the offer in the 4th campaign, 0 otherwise.
- **AcceptedCmp5**: 1 if the customer accepted the offer in the 5th campaign, 0 otherwise.
- **Response**: 1 if the customer accepted the offer in the last campaign, 0 otherwise.
- **Z_CostContact**: A Constant cost per contact for the marketing campaign.
- **Z_Revenue**: A revenue generated from each contact.

## Project Objectives

1.**Exploratory Data Analysis (EDA)**:
   - Analyze customer demographics and purchasing behavior.
   - Identify patterns and trends in the data.
   - Visualize key metrics and insights.

3. **Data Cleaning and Preprocessing**:
   - Handle missing values and outliers.
   - Convert categorical variables into numerical formats.
   - Feature scaling and normalization.

4. **Feature Engineering**:
   - Create new features to enhance model performance (e.g., Customer Lifetime Value, Social Media Engagement Score, Product Affinity Scores, Sentiment Analysis).
   - Select the most relevant features for modeling.

5. **Modeling and Prediction**:
   - Build predictive models to forecast customer responses to marketing campaigns.
   - Evaluate model performance using appropriate metrics (e.g., accuracy, precision, recall).
   - Optimize models for better predictions.

6. **Insights and Recommendations**:
   - Provide actionable insights based on the analysis.
   - Suggest strategies to improve customer engagement and campaign effectiveness.

## Prerequisites

- Python 3.7 or higher
- Jupyter Notebook
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, nltk (for sentiment analysis)

## Installation and Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/marketing-campaign-analysis.git
    cd marketing-campaign-analysis
    ```

2. Install required packages:
    ```bash
    pip install -r requirements.txt
    ```

3. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/rodsaldanha/arketing-campaign/data) and place it in the project directory.

## Getting Started

1. Open the `Marketing_Campaign_Analysis.ipynb` notebook to follow the analysis steps.
2. Run the cells to execute the data cleaning, EDA, feature engineering, and modeling processes.
3. Modify and adapt the code to explore different aspects of the dataset or to integrate new data.

## Results

- The notebook will provide visualizations and metrics summarizing the key findings.
- Predictive models will be evaluated and compared to identify the best performing model.
- Insights and recommendations will be presented at the end of the notebook.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.

## Acknowledgements

- Thanks to [Kaggle](https://www.kaggle.com/datasets/rodsaldanha/arketing-campaign/data) for providing the dataset.
- Special thanks to all the contributors and the data science community for their support and resources.
