# Credit card fraud detection project

## Table of Contents

- [Project Overview](#Project-overview)
- [Dataset](#Dataset)
- [Project Repository Structure](#Project-Repository-Structure)
- [Project Dependencies](#project-dependencies)
- [Project Workflow](#project-workflow)
- [Results and Insights](#results-and-insights)
- [Conclusion](#conclusion)
- [Acknowledgments](#acknowledgments)
- [Contact Information](#contact-information)

## Project Overview

This project is dedicated to detecting fradulent credit card transaction thus providing a basic insight to assist in detecting real time fraud transaction 

## Dataset

The dataset is sourced from Kaggle. It contains credit card transactions made by European cardholders in September 2013. This dataset presents transactions that occurred in two days (284,807 transactions), out of it 492 are fraud transactions. 
N.B.: The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.
Features V1, V2, … V28 are the principal components obtained with PCA, except the 'Time' and 'Amount'. Feature. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

## Project Repository Structure

The repository is organized as follows:

1. **images/**: Contains images used within this README.
2. **Data/**: Stores the dataset used for analysis.
3. **README.md**: This document, gives an overview of the project.
6. **ipynb notebook/**: Contains a Jupyter notebook with the full co.
7. **cc_model.pkl**: This is the final model.

## Project Dependencies

This project is developed using Python and depends on following libraries:

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- imblearn (for balancing the classes)

Ensure all the libraries are installed and imported before running the code to avoid errors.

## Project Workflow

1. **Data Preparation**: The dataset was cleaned carefully and prepared to ensure data quality thus to build an efficent model.
2. **Data Analysis**: The dataset was explored through different data visualizations and analysed to uncover patterns and trends.
3. **Modeling**: A detection model was built using ML algorithms, including Logistic Regression and Decision Tree to detect fraud transaction based on the dataset.
4. **Model Evaluation**: Models were assessed using various metrics, and the best-performing model was chosen.
5. **Hyperparameter Tuning**: The hyperparameters of the selected model were fine-tuned to enhance prediction accuracy.
6. **Insights and Recommendations**: Valuable insights were drawn from the analysis, and data-driven recommendations were offered to stakeholders.
7. **Conclusion and Next Steps**: The project's findings and key factors influencing sales were summarized, along with suggested actions for future marketing efforts.

## Results and Insights

The analysis of sales data led to several critical insights, including:

- Channel Effectiveness: TV advertising was identified as the most impactful channel for sales, with a significant positive correlation.

- Diminishing Returns: There's a point of diminishing returns for each advertising channel, emphasizing the need for an optimal budget allocation.

- Radio and Newspaper Distributions: Radio advertising spending is normally distributed and relatively evenly spread, making it a stable choice. Newspaper spending, on the other hand, exhibits positive skew, indicating less common high spending.

- Sales and TV Distributions: Sales data is symmetric, while TV advertising has a concentration of higher spending, suggesting the need for an in-depth analysis of high TV advertising expenditures.

## Conclusion 

In conclusion, this project has illuminated the path to optimizing sales through data-driven insights. For future endeavors, consider the following steps:

By implementing these steps, you can optimize your advertising budget allocation, increase sales, and maintain competitiveness in the market.

## Acknowledgments

I would like to express my appreciation to CodSoft for providing this valuable learning opportunity. This project has been instrumental in advancing my data analysis and machine learning skills.

## Contact Information

For further information, please contact:

Abhinandh C S
Email: abhinandhcs77@gmail.com
