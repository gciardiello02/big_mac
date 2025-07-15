# 🌍 Big Mac Overvaluation Predictor 🍔
🔎 What Is This?
This app predicts whether a Big Mac is overvalued or not overvalued in a given country, based on the world-famous Big Mac Index by The Economist.

Built with R Shiny and powered by XGBoost, it uses real economic features like exchange rates and price indexes to make fast, accurate predictions.

🧠 How It Works
You enter the following:

🍔 Local Big Mac price

💱 Exchange rate (local currency per USD)

📊 Raw indexes vs major currencies: USD, EUR, GBP, JPY, CNY

📆 Year

🌍 Country

And the app tells you:

Is the Big Mac overvalued in this country?

🔗 👉 Try the app live

📊 Model Performance (Test Set)
✅ Accuracy: 98.6%

📈 Sensitivity (Overvalued): 90.9%

🔒 Specificity (Not Overvalued): 100%

Model trained using the tidymodels framework and deployed with vetiver.

🚀 What’s Next?
Add macroeconomic indicators like inflation, GDP, etc.

Test the model with live, streaming data

Expand coverage to more countries and years

🛠️ Tech Stack
R: Shiny, tidymodels, vetiver, xgboost

Deployment: Hugging Face Spaces

Version control: GitHub
