📊 Predicting Online Ad Clicks using Machine Learning

Kaggle link to the notebook and its outputs : https://www.kaggle.com/code/dorislacassagne/ad-click-prediction

📌 Project Overview

This project focuses on predicting whether a user will click on an online advertisement based on various factors such as demographics, browsing behavior, ad display context, and time of day. The goal is to leverage machine learning techniques to improve ad targeting strategies, optimize ad placement, and gain insights into user interactions with online advertisements.

🔍 Dataset Description

The dataset contains:
- id: Unique identifier for each user.
- full_name: User's name formatted as "UserX" for anonymity.
- age: Age of the user (ranging from 18 to 64 years).
- gender: The gender of the user (categorized as Male, Female, or Non-Binary).
- device_type: The type of device used by the user when viewing the ad (Mobile, Desktop, Tablet).
- ad_position: The position of the ad on the webpage (Top, Side, Bottom).
- browsing_history: The user's browsing activity prior to seeing the ad (Shopping, News, Entertainment, Education, Social Media).
- time_of_day: The time when the user viewed the ad (Morning, Afternoon, Evening, Night).
- click: The target label indicating whether the user clicked on the ad (1 for a click, 0 for no click).

The challenge is to clean and preprocess the data, explore its structure, and apply predictive models to determine the likelihood of an ad click.

🛠️ Workflow
- Handling missing values
- Visualize distributions
- Encode categorical features as a one-hot numeric array
- Normalize/scale numerical features
- Comparing different classification models (Logistic Regression and Random Forest)

🛠️ Technologies Used
- Python (Pandas, NumPy, Sklearn, Matplotlib)
- Kaggle Notebooks for experimentation
- Machine Learning models for classification

📢 Feel free to explore the code and contribute! 🚀
