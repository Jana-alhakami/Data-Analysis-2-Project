# Data-Analysis

# Project Title: Machine Learning Projects - Naive Bayes, Market Basket Analysis, and Text Analysis

## Overview

This repository contains three distinct machine learning tasks:

1. **Naive Bayes Classifier for Breast Cancer Diagnosis**: Implementation of a Naive Bayes classifier to predict whether a breast tumor is benign or malignant.
2. **Market Basket Analysis on the Online Retail Dataset**: Using association rule learning techniques to discover product associations.
3. **Text Analysis of Amazon Fine Food Reviews Dataset**: Sentiment analysis using machine learning to classify positive or negative reviews.


## Folder Structure

```
Data-Analysis/       
│
├── Naive_Bayes/       
│   ├── NBTask.pdf  # Report for Naive Bayes Classifier for Breast Cancer Diagnosis       
│   ├── Naive_Bayes.py  # Python script for Naive Bayes implementation       
│   └── dataset/  # Dataset for Breast Cancer Diagnosis (if needed for code execution)       
│
├── Market_Basket_Analysis/       
│   ├── Market_Basket_Analysis_Report.pdf  # Report for Online Retail Dataset Market Basket Analysis       
│   ├── Market_Basket_Analysis.py  # Python script for Market Basket Analysis       
│   └── dataset/  # Online Retail dataset (link or storage)       
│       
├── Text_Analysis/       
│   ├── Text_Analysis_of_Amazon_Fine_Food_Reviews_Dataset.pdf  # Report for Text Analysis of Amazon Fine Food Reviews Dataset       
│   ├── Text_Analysis.py  # Python script for Text Analysis       
│   └── dataset/  # Amazon Fine Food Reviews dataset (link or storage)       
│       
├── Install necessary dependencies  
│   
│   To ensure smooth execution of all scripts, please install the following libraries:
│   - pandas
│   - scikit-learn
│   - matplotlib
│   - seaborn
│   - mlxtend
│   - wordcloud
│   - plotly
│   - apriori
│   - association_rules
│       
├── Datasets
│   - Breast Cancer Wisconsin (Diagnostic): UCI Machine Learning Repository
│   - Online Retail Dataset: UCI Machine Learning Repository
│   - Amazon Fine Food Reviews Dataset: Available on Kaggle
│       
└── README.md
```

## Installation and Requirements

To install the required dependencies, you can use the `requirements.txt` file by running:

```
pip install -r requirements.txt
```

Ensure that you have Python 3.6 or above.

## Usage

- **Naive Bayes Classifier**: Navigate to the `Naive_Bayes` folder and run the script `Naive_Bayes.py` to train and test the model on the Breast Cancer dataset.
- **Market Basket Analysis**: Navigate to the `Market_Basket_Analysis` folder and run `Market_Basket_Analysis.py` to perform association rule learning on the Online Retail dataset.
- **Text Analysis**: Navigate to the `Text_Analysis` folder and run `Text_Analysis.py` to classify the sentiment of the Amazon Fine Food Reviews dataset.

## Reports

Each task includes a detailed report that explains the methodology, data preprocessing, modeling, evaluation, and conclusions drawn from the analysis:

- `NBTask.pdf` for Naive Bayes Classifier for Breast Cancer Diagnosis
- `Market_Basket_Analysis_Report.pdf` for Market Basket Analysis
- `Text_Analysis_of_Amazon_Fine_Food_Reviews_Dataset.pdf` for Text Analysis of Amazon Reviews

## Datasets

- **Breast Cancer Wisconsin (Diagnostic)**: This dataset is available on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)).
- **Online Retail Dataset**: Available on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/online+retail).
- **Amazon Fine Food Reviews Dataset**: Available on [Kaggle](https://www.kaggle.com/snap/amazon-fine-food-reviews).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or collaboration inquiries, feel free to contact the repository maintainer.

---

Happy analyzing!

