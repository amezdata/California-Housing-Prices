# California-Housing-Prices
author: R.H. Amezqueta <br>
date: 12-15-2024

## Overview:
This project focuses on developing and optimizing machine learning models to predict median housing prices in California, leveraging a dataset with features such as geographical location, population density, housing characteristics, and socioeconomic factors. The ultimate goal is to create an accurate and interpretable model that provides actionable insights into the drivers of housing prices while analyzing their economic implications.

## Introduction:
The dataset was extracted from the 1990 California census and includes information about houses within various districts, along with summary statistics for each district. Despite being based on 1990s data, the application of machine learning models to this dataset provides valuable insights and practical utilities in modern contexts. These models capture long-term patterns and relationships, such as the influence of income, proximity to the coast, and population density on housing prices, which remain relevant today. They can serve as a baseline for updating with modern data, help test housing market assumptions, simulate economic scenarios, and educate analysts and policymakers on housing market dynamics. While absolute price predictions need adjustment for inflation and contemporary factors, the insights into variable interactions are still applicable for regional comparisons, retrospective analyses, and understanding market trends. Additionally, the utility of these models will be enhanced by testing both manual models and AutoML approaches, ensuring a comprehensive evaluation of model performance and ease of use in various applications.

## Methodology
* Exploratory Data Analysis (EDA):
  - Conducted an initial analysis to understand the dataset's structure and key characteristics.
  - Visualized California districts on a map and created a heatmap to display median house prices.
* Algorithm Testing:
  - Tested multiple algorithms to evaluate how the dataset behaved.
  - Selected the most promising algorithms for further optimization.
* Baseline Model Creation:
  - Used H2O AutoML to develop baseline models with the dataset in its original form.
* Feature Engineering:
  - Created new features by combining existing ones to enhance predictive power.
* Model Optimization:
  - Conducted parameter search and tuning for selected algorithms, incorporating engineered features.
  - Extracted the most relevant features for final model improvement.
* Performance Comparison:
  - Compared results across all models to identify the best-performing approach.tegy.

## Data Limitations:
This analysis faces several limitations that could impact the accuracy and generalizability of the models. The dataset lacks important variables that significantly influence housing prices, such as proximity to amenities, specific property features, or broader economic indicators like interest rates and unemployment rates. These omissions limit the models’ ability to capture the full complexity of housing price determinants. As mentioned before, its basis on 1990 census data makes the models less relevant for modern markets unless updated. Additionally, the capped data at $500,001 also poses challenges, as models may still struggle to represent high-value properties accurately despite engineering adjustments.
