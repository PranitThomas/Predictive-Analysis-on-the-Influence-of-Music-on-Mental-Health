
# 🎵 Predictive-Analysis-on-the-Influence-of-Music-on-Mental-Health 🎶

## Overview

This project proposes the development of a predictive model that analyzes the relationship between music preferences and mental health outcomes. By utilizing a diverse dataset, this model aims to identify patterns and correlations between individuals' music choices and psychological parameters like 'Conscientiousness', 'Neuroticism', Extraversion, K-10 scores and other personality traits. Users will be able to input their personal data regarding music preferences, lifestyle, and mental health status, and receive tailored predictions related to their mental health indicators.

## Table of Contents
- [Project Overview](#overview)
- [Features](#features)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Installation](#installation)
- [Technologies](#technologies)
- [Contributing](#contributing)

## Features
- 🎶 **Music Theory Analysis**: Analyze musical relationship between music preferences and mental health outcomes.
- 📈 **Predictive Models**: Implement machine learning models to predict how different musical preferences influence mental health metrics.
- 📊 **Data Visualization**: Utilize XGBoost for feature importance analysis and model performance evaluation.
- 🧠 **Mental Health Analytics**: Use psychological datasets to assess the emotional and cognitive impact of musical patterns.

## Dataset
- **Music Dataset**: Contains features such as Openness, Conscientiousness, Agreeableness, etc.
- **Mental Health Dataset**: Includes user-reported emotional responses and mental health metrics.

> **Note**: For ethical reasons, anonymized and publicly available datasets are used.

## Methodology
1. **Data Collection**: Gather and preprocess musical features and mental health-related data.
2. **Feature Extraction**: Extract key features like  'Unhealthy', 'Healthy', 'K-10' (mental health scale), and personality traits (Openness, Conscientiousness, Extraversion, Agreeableness, Neuroticism).
3. **Modeling**: Build predictive models (e.g., linear regression, randomForest, XGBoost) to study the correlation between music and mental health.
4. **Evaluation**: Validate models using metrics such as R2 Score.

## Installation
To set up the project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/PranitThomas/Predictive-Analysis-on-the-Influence-of-Music-on-Mental-Health
    cd Predictive-Analysis-on-the-Influence-of-Music-on-Mental-Health
    ```

2. Create a virtual environment and activate it:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required dataset:
    ```bash
    pip install -r User_scores_nonPII2.0.csv
    ```

## Technologies
- Python, Jupyter
- Pandas, NumPy (Data processing)
- Scikit-learn, TensorFlow, XGBoost (Machine learning)
- Matplotlib, Seaborn, joblib (Data visualization)

## Contributing
Contributions are welcome! If you'd like to collaborate, please fork the repository and submit a pull request.

1. Fork the repository.
2. Create a new branch for your feature: `git checkout -b feature-branch`.
3. Commit your changes: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature-branch`.
5. Open a pull request.
