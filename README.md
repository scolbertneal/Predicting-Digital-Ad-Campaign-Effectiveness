# Predicting-Digital-Ad-Campaign-Effectiveness
Help marketing teams predict which digital ad campaigns (email, social, display) are likely to perform best based on content type, audience segment, and channel.


# 📈 Digital Marketing Campaign Performance: ML Analysis

Hi! 👋 This notebook is part of a project I worked on for my AI master's program. The goal was to build and evaluate machine learning models to predict the success of digital marketing campaigns based on historical campaign data.

## 🔍 Project Overview

Marketing teams often launch campaigns without knowing ahead of time which ones will drive engagement. In this project, I used Python and machine learning to build a predictive model that helps estimate whether a digital campaign will result in a conversion or not. This kind of tool can help marketers better allocate budgets and tailor strategies.

## 🧠 What I Did

* Cleaned and preprocessed a marketing dataset (removed nulls, encoded categories)
* Performed EDA (exploratory data analysis) to understand distributions
* One-hot encoded key categorical features like `Gender`, `CampaignChannel`, and `AdvertisingPlatform`
* Trained multiple models:

  * Logistic Regression
  * Random Forest
  * XGBoost
* Compared model performance using accuracy, precision, recall, and F1-score
* Visualized the results to make comparisons easier
* Suggested model improvements and next steps based on results


## 🛠 Tools & Libraries

* Python (pandas, numpy, seaborn, matplotlib)
* Scikit-learn (LogisticRegression, RandomForestClassifier)
* XGBoost
* Jupyter Notebook


## 📊 Results

The Random Forest and XGBoost models performed better than Logistic Regression, with XGBoost showing the best balance across all metrics. It was especially good at capturing minority class predictions, which is key when conversion rates are low.


## 💡 Next Steps

If I had more time, I’d:

* Do hyperparameter tuning for the models
* Use feature importance to inform campaign design
* Explore using text inputs (like campaign copy) with NLP-based models
* Try AutoML libraries to test more model combinations


## 🧑‍💻 Author

**Samantha Colbert**
HCP Digital Marketing Specialist @ Kenvue
Master's student in Artificial Intelligence 🎓
