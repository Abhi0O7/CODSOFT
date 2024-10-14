# Credit Card Fraud Detection 

<img src="card.jpg" width="300" height="250">

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

This project focuses on identifying fraudulent credit card transactions, aiming to provide insights that help detect real-time fraudulent activities.

## Dataset

The dataset, sourced from Kaggle, includes credit card transactions made by European cardholders in September 2013. It covers two days of transactions (284,807 in total), with 492 marked as fraudulent.

Note: The dataset is highly imbalanced, with the fraudulent class representing just 0.172% of all transactions.

The features V1 through V28 are the principal components derived from PCA, while 'Time' and 'Amount' are not transformed. The 'Class' feature is the target variable, where 1 indicates fraud, and 0 indicates a legitimate transaction.

 
[**Dataset Link**](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

## Project Repository Structure

The repository is organized as follows:

1. **README.md**: Provides an overview of the project.
2. **ipynb notebook/**: Contains a Jupyter notebook with the full code.
3. **cc_model.pkl**: This is the final model.

## Project Dependencies

This project is developed using Python and depends on following libraries:

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- imblearn (for balancing the classes)

Make sure to install these libraries and import before running the code to avoid errors.

## Project Workflow

1. **Data Pre-Processing**: The dataset was cleaned carefully and prepared to ensure data quality thus to build an efficent model.
   
2. **Exploratory Data Analysis**: The dataset was explored through different data visualizations and analysed to better understand the data we are dealing with.
   
3. **Classification model**: The credit card fraud detection problem is a classification problem, as it involves classifying a credit card transaction to be in either of the two classes – valid or fraudulent, here classification algorithms including Logistic Regression and Decision Tree are used for the same.
   
4. **Model Evaluation**: Model evaluation involves testing the model's performance on unseen data by comparing its predictions (Y_pred) to the true values (Y_test).Here for classification tasks, key metrics like accuracy, precision, recall and F1 score are used.
   
5. **Conclusion**: This project provides a baseline model for real-world fraud detection systems, further improvements could be made by experimenting with advanced algorithms.

## Results and Insights

After applying Logistic Regression and Decision Tree models to the dataset, the following results were obtained:


   ===**Logistic Regression**===

 Accuaracy: 0.9444656419201279
 
 Precision: 0.9728605694831322
 
 Recall: 0.9143683071832446
 
 F1 Score: 0.9427079916400342
 

   ===**Decision Tree Classifier**===
   
 Accuaracy: 0.9982194120425888
 
 Precision: 0.9974405053640473
 
 Recall: 0.9990000545424795
 
 F1 Score: 0.9982196708207682

Despite good performance, further improvements could be made by:

* Trying more advanced models like Random Forest, XGBoost, or deep learning-based algorithms.
* Fine-tuning hyperparameters or experimenting with ensemble methods to improve recall and reduce the number of missed frauds.
* Utilizing anomaly detection techniques to identify fraud in a more unsupervised manner, which could be helpful for future work with larger and more complex datasets.

## Conclusion 

This project provides a baseline model that can be adapted and improved for real-world fraud detection systems using machine learning. Decision Tree slightly outperformed the Logistic Regression model in terms of precision and recall, making it a better choice for this specific dataset. However, both models performed well overall.

Given the highly imbalanced nature of the dataset, We handled class imbalance through techniques such as Oversampling using the imblearn library, this significantly improved the model’s ability to detect fraud transactions. 
Further improvements could be made by experimenting with advanced algorithms like Random Forest, XGBoost, or deep learning techniques for better performance.

## Acknowledgments

I would like to express my gratitude to Kaggle for providing the dataset used in this project. Additionally, I would like to thank the open-source community for the valuable resources and tools and last but not least, all others especially You Tube tutors who made this project possible.

## Contact Information

For further information, please contact:

Abhinandh C S

Email: abhinandhcs77@gmail.com
