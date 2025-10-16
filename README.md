# 🤖 AI for SDG 2: Advanced Crop Yield Prediction

### ## 🚀 Elevator Pitch Deck

You can download or view the full presentation PDF by clicking the link below:

[**View my Pitch Deck Presentation **](https://www.canva.com/design/DAG1-t0-3ZI/MH6rylOw9u9GgJmGBYeagg/edit?utm_content=DAG1-t0-3ZI&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)


This project addresses the **United Nations Sustainable Development Goal 2: Zero Hunger** by developing a comprehensive machine learning solution to predict crop yields. Going beyond a simple prediction, this project scientifically compares multiple models, explains the key factors driving yield, and includes an interactive tool for real-time forecasting.

---

### ## 🎯 The Problem: Unpredictable Yields and Food Insecurity

Food security is a critical global challenge. Farmers, especially small-scale farmers, face immense uncertainty due to changing weather patterns, rainfall variability, and temperature fluctuations. This unpredictability leads to:

* **Food Shortages**: Difficulty for governments and aid organizations to anticipate and prepare for poor harvests.
* **Economic Instability**: Farmers can face financial ruin from a single failed crop season.
* **Inefficient Resource Use**: Without accurate forecasts, resources like water and fertilizer may be used inefficiently.

---

### ## 💡 Our Solution: An Explainable and Interactive AI

We developed an end-to-end machine learning solution that not only predicts crop yields with high accuracy but also provides actionable insights.

Our approach involved three key steps:
1.  **Rigorous Model Selection**: We trained and compared three different regression models (Linear Regression, Random Forest, and Gradient Boosting) to scientifically determine the best performer.
2.  **Explainable AI (XAI)**: We analyzed our best model (Random Forest) to identify the most critical factors influencing crop yield.
3.  **Interactive Tool**: We built a simple user interface directly within the notebook, allowing anyone to input conditions and receive an instant yield prediction.

---

### ## 📊 Model Performance: Selecting the Best Tool for the Job

To ensure our predictions were as accurate as possible, we compared three models. The **Random Forest Regressor** demonstrated superior performance, making it our final choice.

| Model                 | R-squared (R²) Score |
| --------------------- | -------------------- |
| **Random Forest** | **0.98** |
| Gradient Boosting     | 0.97                 |
| Linear Regression     | 0.76                 |

The R-squared ($R^2$) score indicates that our chosen model can explain **98%** of the variability in crop yield, which is an exceptionally strong result.

---

### ## 🧠 Key Insights: What Drives Crop Yield?

A good model doesn't just predict; it teaches us *why*. By analyzing our Random Forest model, we identified the most influential factors for predicting crop yields. This insight is crucial for farmers and policymakers.

![project screenshot](https://imgur.com/Yq2z1IF.png)

My analysis shows that factors like **average temperature, pesticide usage, and the specific crop type** are the most significant drivers of the final harvest size.

---

### ## 🚀 Interactive Demo: Predict a Harvest!

To bring the model to life, I created a simple interactive prediction tool. This prototype demonstrates how the final solution could be deployed as a web or mobile app to help farmers on the ground. Users can select a country, a crop, and input environmental conditions to get an instant yield forecast.


![project screenshot](https://imgur.com/GIx9bjD.png)


---

### ## ⚙️ How to Run the Project

You can easily run this project yourself using Google Colab.

1.  **Download Files**: Download the Python script (`.py`) and the `yield_df.csv` dataset from this repository.
2.  **Open Google Colab**: Go to [colab.research.google.com](https://colab.research.google.com) and upload the `.py` notebook.
3.  **Upload Dataset**: In the Colab interface, use the folder icon on the left sidebar to upload the `yield_df.csv` file.
4.  **Run the Code**: In the menu, go to **Runtime > Run all**. The script will execute, perform the model comparison, and display the interactive tool at the end.

---

### ## 🤔 Ethical Considerations

* **Data Bias**: The training data may not equally represent all countries. Predictions for underrepresented regions might be less accurate.
* **Accessibility**: To be effective, this technology must be accessible to small-scale farmers, not just large corporations, perhaps through a free and easy-to-use mobile app.
* **Sustainability**: By identifying key factors, the model can help promote more sustainable practices, optimizing the use of resources like pesticides and water.

  ###AUTHOR
  **MAKAMU OKINYI BETSY**
  
  *EMAIL* makamubetsy@gmail.com
