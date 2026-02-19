# Hi, I'm Yulia

I'm a **Data Analyst & Automation Specialist** who enjoys working at the intersection of data, machine learning and business process automation.

Based in Germany | Open to opportunities in Data & Automation

---

### Tech Stack

**Languages & Tools:** Python, SQL, Git, GitHub, Jupyter Notebook

**Data & ML:** Pandas, NumPy, Scikit-learn, XGBoost, ETL, EDA, Feature Engineering, Classification, Regression, Clustering, Anomaly Detection, PCA

**Visualization:** Power BI (DAX), Tableau, Matplotlib, Seaborn, Plotly, Folium

**Deployment & Apps:** Streamlit, Gradio, HuggingFace Spaces

**Platforms:** Pega Platform (Constellation, App Studio, Dev Studio, Decisioning)

---

### Featured Projects

#### [US Pollution Analysis](https://github.com/YShutko/in_process_US_pollution_analysis) 
End-to-end analysis of ~1.4 million EPA air quality measurements across the US covering NO₂, SO₂, CO, and ozone. Pipeline covers ETL (Parquet conversion, geocoding, unit standardization, AQI recalculation), EDA, and four ML tasks: regression to predict ozone concentration, multi-class AQI classification, feature importance analysis, and anomaly detection via Isolation Forest. Identified clear seasonal and geographic pollution patterns and significant cross-pollutant relationships.

#### [Spotify Track Analysis and Popularity Prediction](https://github.com/YShutko/spotify_track_analysis_and_prediction)
Full pipeline from ETL and feature engineering (interaction terms, artist popularity proxy, macro-genre grouping) through to ML modeling. Random Forest and tuned XGBoost both achieved R² ≈ 0.80 and MAE ≈ 5, significantly outperforming the Linear Regression baseline (R² ≈ 0.25). Key finding: artist popularity dominates predictions, while audio features alone have limited linear predictive power. Delivered interactive prediction tools (ipywidgets, Gradio) and a [Streamlit app deployed on HuggingFace](https://huggingface.co/spaces/YShutko/spotify-popularity-app).

#### [Human Activity Recognition — PCA, Classification & Clustering](https://github.com/YShutko/human_activity_recognition_using_smartphone_unsupervised_ml)
Applied PCA as a dimensionality reduction technique to 561-feature smartphone sensor data (10,299 samples). Gradient Boosting achieved 98.9% accuracy without PCA; Logistic Regression reached 98.0% and proved more resilient to dimensionality reduction. K-Means clustering with Silhouette Score ≈ 0.11 confirmed that K-Means is unsuitable for this dataset due to overlapping activity clusters.

#### [Rain Prediction in Canberra](https://github.com/YShutko/rain_prediction_using_classification_models)
Binary classification on 10 years of Australian weather data (3,436 Canberra observations). Best model: KNN with GridSearchCV — 89.9% accuracy, F1 ≈ 0.82, ROC AUC ≈ 0.95. Humidity and pressure emerged as top predictors, with RainToday showing the strongest correlation (+0.52) to next-day rain.

#### [House Price Prediction — Kansas City](https://github.com/YShutko/House_Price_Prediction_Linear_Regression_Models)
Compared linear, polynomial, and Ridge regression models on 21,613 house sales. Best model: Ridge Regression with degree-2 polynomial features (R² = 0.75, α = 0.1). Interior living area and construction grade were the strongest price predictors. Higher polynomial degrees (3, 4) caused severe overfitting, underscoring the importance of regularization.

#### [Fitness Patterns and Performance Analysis](https://github.com/YShutko/CI_fitness_patterns_and_perfofmance_analysis)
Classified gym members' fitness levels using a Random Forest model trained on physiological and behavioral data. Confirmed strong correlations: session duration vs. calories burned (~0.91), workout frequency vs. experience level (~0.84). Delivered a 4-page interactive Power BI dashboard (KPIs, decomposition trees, bubble plots, heatmaps) for both technical and non-technical audiences.

#### [Car Price Analysis](https://github.com/YShutko/CI_car_price_analysis) *(Hackathon — Team Ladybug)*
Team hackathon project analyzing pricing patterns across 205 cars. Confirmed that engine size and horsepower are the strongest price drivers; luxury European brands command the highest median prices. Delivered a multi-page Tableau dashboard covering brand positioning, regional market segmentation, and performance-efficiency trade-offs.

#### [Bank Churners Analysis](https://github.com/YShutko/CI_bank_churners_analysis)
EDA-focused analysis of credit card customer churn. Key finding: inactivity (months inactive) is the strongest behavioral churn predictor, while demographic features alone show limited predictive power. Churn is concentrated almost entirely in Blue cardholders. Used difference heatmaps and interactive Plotly visualizations to surface insights for retention strategy.

#### [The Battle of the Neighborhoods](https://github.com/YShutko/IBM_the_battle_of_neighborhoods)
IBM Data Science capstone using the Foursquare API to analyze and cluster city neighborhoods by venue category and frequency. Applied KMeans clustering and geospatial visualization with geopy and Folium to generate location-based business insights.

---

### What I Enjoy
Turning messy data into clean insights. Building dashboards people actually use. Automating processes so teams can work smarter, not harder.

---

### Get in Touch

- GitHub: [github.com/YShutko](https://github.com/YShutko)
- LinkedIn: [Yulia Shutko](https://www.linkedin.com/in/yulia-shutko-a73193161/)
