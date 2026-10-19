# Google Play Store Analysis | Then vs. Now

### Revisiting My First Data Analysis Project Two Years Later

What happens when you revisit one of your earliest data analysis projects after two years of learning and experience?

That was the question behind this project.

I originally analysed Google Play Store data as a beginner, focusing on data cleaning, exploratory visualisation and predicting app ratings using machine learning.

Two years later, I returned to the same dataset with a different perspective. Rather than immediately focusing on building a predictive model, I wanted to explore what the data could reveal about app adoption, user engagement, pricing and market behaviour.

This repository brings both versions together to document how my approach to data analysis has evolved.

## The Two Approaches

### 01 | The Original Analysis — Beginner Me

**Focus:** Exploratory Data Analysis & Rating Prediction

My original project involved:

- Cleaning and preprocessing Google Play Store data.
- Exploring app categories, ratings, reviews and installations.
- Visualising relationships between app characteristics.
- Building a Random Forest regression model to predict app ratings.

**Tools:** Python, Pandas, Matplotlib, Seaborn, Scikit-learn

[View Original Notebook](01_original_analysis/GooglePlaystoreAppsRatingPrediction.ipynb)

### 02 | The Revisited Analysis — Two Years Later

**Focus:** Market Analysis & User Engagement

For the revisited project, I shifted my attention towards understanding the dataset and interpreting its patterns.

The analysis explores:

- App adoption and installation patterns.
- User engagement through reviews and ratings.
- Differences across app categories.
- Free versus paid app characteristics.
- Pricing and update recency.

Rather than treating predictive modelling as the default destination, the objective was to investigate meaningful patterns and communicate what they suggest about the app marketplace.

**Tools:** Python, Pandas, Exploratory Data Analysis, Statistical Analysis, Data Visualisation

[View Revisited Notebook](02_revisited_analysis/market_user_engagement_analysis.ipynb)

## What Changed?

| Beginner Me | Two Years Later |
|---|---|
| Focused on completing an analysis and building a model | Focused on defining and investigating analytical questions |
| Explored variables and visualised patterns | Considered how patterns relate to adoption, engagement and market behaviour |
| Treated prediction as a central objective | Recognised that useful analysis does not always require prediction |
| Concentrated on applying technical methods | Placed greater emphasis on interpretation and analytical communication |

## Repository Structure

```text
google-play-store-analysis/
├── 01_original_analysis/
│   └── GooglePlaystoreAppsRatingPrediction.ipynb
├── 02_revisited_analysis/
│   ├── market_user_engagement_analysis.ipynb
│   └── README.md
├── data/
│   ├── googleplaystore.csv
│   └── README.md
└── README.md
```

## Dataset

Both analyses use Google Play Store app data, covering characteristics such as app categories, ratings, reviews, installations, pricing and update information.

The dataset is stored once in the `data/` directory and shared across both versions.

## Key Reflection

Revisiting this project reminded me that growth in data analytics is not simply about learning more tools or building more complex models.

It is also about asking better questions, examining the reliability of the data, recognising analytical limitations and communicating findings in a way that makes them useful.

The dataset remained the same. My approach to analysing it changed.

---

*This is a self-directed portfolio project documenting my development in data analysis.*
