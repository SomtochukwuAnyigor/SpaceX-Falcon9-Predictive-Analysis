SpaceX Falcon 9 First Stage Landing Prediction
Project Overview

The goal of this project is to predict whether the Falcon 9 first stage will land successfully. This is a critical question in the space industry because a successful landing reduces the cost of a launch from $165 million to $62 million. By predicting the likelihood of a successful landing, we can determine the cost of a launch.
Technical Workflow

    Data Collection: Used the SpaceX API and Web Scraping to gather historical launch data.

    Exploratory Data Analysis (EDA): Used SQL and Matplotlib/Seaborn to identify trends in launch sites and payload masses.

    Interactive Visualization: * Created map-based analytics using Folium.

        Developed a real-time dashboard using Plotly Dash.

    Machine Learning: Built and tuned classification models including Logistic Regression, SVM, Decision Tree, and KNN to predict landing outcomes.

Key Findings

    Best Model: All models (Logistic Regression, SVM, Decision Tree, and KNN) performed similarly on the test set with an accuracy of approximately 83.33%.

    Payload Impact: Success rates generally increase as payload mass increases, particularly for the "FT" (Full Thrust) booster version.

    Geography: Kennedy Space Center (KSC LC-39A) has the highest number of successful launches.

Tools Used

    Languages: Python (Pandas, NumPy, Scikit-Learn)

    Visualization: Matplotlib, Seaborn, Folium, Plotly Dash

    Database: SQL

    Platform: Google Colab & GitHub
