# 📊 Data Science & Industrial Engineering Portfolio
**Author:** Muhammad Zaka Shaheryar  
**Focus Areas:** Machine Learning, Big Data Analytics, Forecasting, Industrial Engineering Applications  

---

## 🔥 Featured Projects

### 1. ⚡ Predicting Energy Demand in Spain (Capstone – CIND 820)
- **Tools:** Python, R, Weka, Tableau, Excel  
- **Dataset:** 35,064 rows × 29 cols (consumption, generation, pricing, weather from ENTSOE, ESIOS, OpenWeather)  
- **Methods:** Regression (Linear, KNN, Decision Tree, Random Forest), Classification (Logistic, KNN, Decision Tree)  
- **Key Results:**  
  - Random Forest Regression → **R² ≈ 0.94** (best for hourly demand forecasting)  
  - Logistic Regression Classifier → **93.5% accuracy** for high-demand days  
- **Impact:** Provides tools for utilities to optimize resource dispatch and reduce GHG emissions.  

---

### 2. 📞 Customer Churn Prediction – Telecommunications Provider (CIND 119, Collaborative)
- **Tools:** Python, R, Excel, SAS  
- **Dataset:** 3,333 customer records, 21 attributes  
- **Methods:** Decision Tree, Naïve Bayes classification  
- **Key Results:**  
  - Decision Tree (baseline): **94% accuracy**, precision 95%, recall 98%  
  - Naïve Bayes: **88% accuracy**  
- **Business Insights:** High churn risk when >264.3 daytime minutes + no voicemail, >3 customer service calls, or no international plan.  
- **Recommendations:** Targeted promotions, loyalty program, priority support line.  

---

### 3. 📈 E-Commerce Data Visualization – DataCo Dataset (DS8007)
- **Tools:** Python (pandas, Seaborn, Matplotlib), Tableau, PyQt5 GUI  
- **Goals:** Explore sales patterns, customer segments, shipping efficiency.  
- **Deliverables:** Interactive Tableau dashboard + PyQt5 application.  
- **Key Insights:**  
  - Europe had **583% sales increase** Y/Y, while Pacific Asia and USCA declined.  
  - Shipping delays of 1 day caused significant profit drops; first-class shipping most profitable.  
- **Impact:** Enabled stakeholders to visualize KPIs and act on inventory & logistics bottlenecks.  

---

### 4. 🤖 Sales Forecasting with Machine & Deep Learning (DS8013)
- **Tools:** Python (scikit-learn, TensorFlow/Keras, Prophet, XGBoost)  
- **Dataset:** DataCo E-commerce sales (2015–2017)  
- **Methods:** Prophet, Random Forest, XGBoost, CNN, LSTM, GRU  
- **Key Results:**  
  - XGBoost → **R² ≈ 0.98, RMSE ≈ 930** (best performer)  
  - CNN improved with tuning (RMSE ↓ from 4658 to 3706), but still below XGBoost.  
- **Impact:** Showed tree-based ML models can outperform deep learning for structured tabular sales data.  

---

### 5. 🧠 Social Determinants of Health & Chronic Disease Outcomes (Collaborative Stem Fellowship Competition)
- **Tools:** Python (XGBoost, LSTM, GRU, SHAP), Pandas, Matplotlib  
- **Dataset:** World Bank (GDP, education, health), WHO (mortality), WIID (inequality), 2000–2021  
- **Focus Diseases:** Alzheimer’s, Asthma, Cardiovascular, Diabetes, Kidney  
- **Key Results:**  
  - XGBoost consistently outperformed deep learning (R² ≈ 0.95 for diabetes mortality).  
  - SHAP showed life expectancy, inequality, and education were top predictors.  
- **Impact:** Informed policymakers on how social determinants shape health outcomes.  

---

### 6. 🌍 Mosaic Migrants – Accessibility & Settlement Analysis (Collaborative Migration Data Challenge)
- **Tools:** GIS, Python/R, Statistics Canada Census 2016/2021  
- **Questions:** How do immigrant classes and generations differ by workplace, school, and healthcare access?  
- **Findings:**  
  - Toronto, Vancouver, Calgary = high newcomer density (>3× national avg).  
  - Women refugees concentrated in urban regions with poor workplace access but good school access.  
- **Impact:** Highlighted inequities in urban planning and immigrant integration.  

---

### 7. 🌎 Life Expectancy Analysis with Big Data Tools (DS8003 Group Project)
- **Tools:** HDFS, Spark, Hive, ElasticSearch, Kibana  
- **Dataset:** World Bank socio-economic indicators (174 countries, 2001–2019)  
- **Findings:**  
  - Global life expectancy ↑ from ~66.7 (2001) → ~72.6 years (2019).  
  - Undernourishment and low income strongly correlated with lower life expectancy.  
- **Impact:** Provided dashboards & visualizations for NGOs and policymakers to prioritize nutrition and sanitation.  

---

### 8. 🤟 Sign Language Recognition – Deep Learning (CIND 860)
- **Tools:** Python, TensorFlow/Keras, scikit-learn  
- **Dataset:** Sign Language MNIST (27k train, 7k test, 28×28 grayscale)  
- **Models:** Random Forest, SVM, XGBoost, CNN, MLP, AlexNet, MobileNet, VGG16, LeNet  
- **Preliminary Results:**  
  - Random Forest: ~98% accuracy (surprisingly strong baseline).  
  - CNN: ~94% accuracy, improving with tuning.  
- **Impact:** Moves toward real-time ASL recognition tools for accessibility.  

---

### 9. 🛒 Superstore Sales Analysis – Data Structures & Efficiency (CIND 830 Team Project)
- **Tools:** Python (pandas, Matplotlib), OOP, Custom Queue structures  
- **Dataset:** Kaggle Superstore Sales (~45k records)  
- **Highlights:**  
  - Implemented linear vs. binary search for promo-day detection (linear faster in practice).  
  - Built queue-based system to simulate order intake.  
  - Created visualizations: top categories, monthly sales trend, scatter of customer vs. sales.  
- **Impact:** Demonstrated efficiency trade-offs, OOP design, and collaborative workflow.  

---

### 10. 📦 Weather Integration, Sales Forecasting & SHAP Explainability (Master Research Projec)

- **Focus:** Forecasting e-commerce sales across the **entire DataCo Supply Chain dataset** using advanced machine learning and deep learning, with explainable AI for transparency.  
- **Tools:** Python (pandas, scikit-learn, CatBoost, XGBoost, Random Forest, LSTM, SHAP, Matplotlib).  
- **Dataset:** ~180k customer orders (2015–2017) with transactional, product, and customer details, enriched with **weather variables** (temperature, humidity, precipitation, wind) from the Visual Crossing API.  
- **Workflow:**  
  - Engineered lagged features (1-, 7-, 30-day sales lags) and integrated weather data.  
  - Trained and compared models: **CatBoost, Random Forest, XGBoost, and LSTM**.  
  - Evaluated performance using **MAE, RMSE, sMAPE, and R²**.  
  - Applied **SHAP (Shapley Additive Explanations)** to interpret model predictions and rank feature importance.  
- **Key Findings:**  
  - **LSTM was the best-performing model**, achieving the highest R² and lowest RMSE/sMAPE among all tested approaches.  
  - Lagged sales features were the strongest predictors; weather features added modest but useful improvements.  
  - SHAP analysis showed that `Product Card ID`, `Sales_Lag_1`, `Order Profit per Order`, and weather lags were the most influential drivers of sales forecasts.  
- **Impact:** Demonstrated that **deep learning (LSTM) combined with explainable AI (SHAP)** provides both **state-of-the-art forecasting accuracy and interpretability**, helping e-commerce businesses improve inventory planning and decision-making.

---


## 🚀 Skills Summary
- **Languages:** Python, R, SQL, Excel, SAS  
- **ML/DL:** Regression, Classification, XGBoost, Random Forest, LSTM/GRU, CNN  
- **Big Data:** Spark, Hive, HDFS, ElasticSearch, Kibana  
- **Visualization:** Tableau, Matplotlib, Seaborn, PyQt5 GUI, GIS tools  
- **Applications:** Forecasting, Churn Prediction, Health Analytics, Social Equity Analysis, Supply-Chain Analytics  

---

## 📫 Contact
- **Email:** zaka.shaheryar@gmail.com
- **LinkedIn:**  https://www.linkedin.com/in/muhammadzaka/
- **GitHub:** https://github.com/Zaka123456
- **Kaggle:** https://www.kaggle.com/zakashah
- **CV:**
