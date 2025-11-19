# Player Engagement Analytics 🎮📊

This project focuses on understanding and predicting player engagement in online games. It combines preprocessing, feature engineering, model training, evaluation, and explainable AI tools to derive actionable insights from gameplay dataset

📘 See the full analysis in the Jupyter Notebook: [understanding-and-predicting-player-engagement-in-online-games.ipynb](understanding-and-predicting-player-engagement-in-online-games.ipynb)

---

## 🔍 Objective

- To classify players into **Low**, **Medium**, and **High** engagement levels based on their personal & gaming behavior. 
- To derive key insights that can help improve user retention and game design.

## 📊 Analytics and Methodology

- **Exploratory Data Analysis (EDA)**:
  - Visualized distributions and correlations of player behaviors.
  - Identified feature importance using correlation heatmaps.

- **Data Preprocessing**:
  - Encoding categorical variables and scaling numerical features.
  - Stratified train-test splitting to maintain engagement class balance.

- **Model Training**:
  - Implemented and compared multiple classifiers:
    - Random Forest
    - Gradient Boosting
    - LightGBM
    - CatBoost
    - Logistic Regression
    - SVC (Support Vector Classifier)

- **Model Evaluation**:
  - Accuracy, AUC, Confusion Matrices, Classification Reports.
  - Summary tables and visual comparison of model performance.

- **Explainable AI**:
  - **SHAP**: Identified global feature importance across the dataset.
  - **LIME**: Explained individual predictions for specific players.

## 📌 Key Insights

- Session duration and frequency are top predictors of engagement.
- Progression metrics (levels, achievements) and difficulty settings influence user retention.
- Personalized incentives and strategy-focused content improve high engagement.

## 🧠 Recommendations

- Implement achievement-based rewards for low/medium engaged players.
- Tailor difficulty settings based on preferred genres and behavior.
- Use explainability tools to build trust in AI-based recommendations.

---

**Author:** Komal Niraula
**GitHub:** [@komalniraula](https://github.com/komalniraula)
