# Data Science Portfolio by Kévin Chok

This repository is to act like a high level overview of the data science projects I've worked on. Each project's `README.md` should act as a full description of the project, but I'll provide a short description here for convenience. All of these projects are in Python. Links are provided to projects whose code can be made public.

## Building Data Infrastructure

[Bike Availability Prediction for Lime using Velib Open Data](https://github.com/kczymchok/block_6_LimeProject)

This project leverages Velib Paris' Open Data (self-service bicycle in Paris) to optimize Lime's bike and scooter deployment by predicting bike availability at Velib stations. Real-time data is ingested using Kafka Confluent and stored in S3, then processed with Airflow to load it into Amazon Redshift. A predictive model estimates bike availability, served via FastAPI. The user interface, built with Streamlit, visualizes bike availability and highlights stations with less than 10% or no bikes available. Docker and Docker Compose ensure seamless deployment and communication between services.

Libraries: Pandas, Numpy, Seaborn, Scikit-Learn

Technology and Tools:

- Kafka Confluent: For real-time data ingestion.
- Amazon S3: Data storage.
- Airflow: ETL processes.
- Amazon Redshift: Data warehousing.
- FastAPI: Serving the predictive model.
- Streamlit: Developing the user interface.
- Docker & Docker Compose: Containerization and deployment.

[Web Scrapping & ETL](https://github.com/kczymchok/bloc_1_kayak_project)

This project aims to recommend the best hotel deals for 5 cities in France based on predefined weather criteria. The process involves collecting geolocation data for cities, weather data, and web scraping the hotels deals on Booking.com, followed by data processing and visualization to provide actionable travel recommendations.


Technology and Tools:

- Selenium: Web scraping for dynamic data (data loaded asynchronously or through JavaScript interactions).
- Beautiful Soup: Web scraping for static data (data embedded directly in the HTML source).
- Amazon S3: Data storage.
- SQLite: Data warehousing.

[GetAround](https://github.com/kczymchok/bloc_5_getaround_project)

This project analyzes rental delays and optimizes pricing for GetAround, a car-sharing service. I implemented a dashboard to visualize data insights on late returns and revenue impact, and developed a machine learning model to predict optimal car rental prices. The project includes a /predict API endpoint and documentation, all hosted online.

Technology and Tools:

- Mlflow: Managing the machine learning lifecycle, including experimentation, reproducibility, and deployment.
- FastAPI: Serving the predictive model.
- Streamlit: Developing the user interface.
- Docker & Docker Compose: Containerization and deployment.
- Heroku: Hosting the API and web application online.


## Machine Learning

[www.datascienceweekly.org: predict the conversion rate](https://github.com/kczymchok/ML_WALMART_project)

In this project, we predict newsletter conversions for www.datascienceweekly.org. The challenge involved performing EDA and preprocessing, training various models to improve the f1-score. The analysis of model parameters provided insights for improving the conversion rate.

[Walmart: predict weekly sales](https://github.com/kczymchok/ML_WALMART_project)

Walmart Inc. tasked us with developing a machine learning model to predict weekly sales across their stores, using various economic indicators. The project involves three main steps: exploratory data analysis (EDA) and preprocessing, training a baseline linear regression model, and fighting overfitting with regularized regression models like Ridge and Lasso. The dataset, derived from a custom Kaggle competition, includes features such as unemployment rate and fuel price. The final deliverables include visualizations, model performance assessments, and feature importance interpretation.

[Uber pickups](https://github.com/kczymchok/ML_clustering_UBER_project)

Uber aims to improve driver availability by identifying hot-zones in New York City using existing pickup data. The project involves developing clustering algorithms (KMeans, DBScan) to find these hot-zones and visualizing them on an interactive dashboard.


## Deep Learning

[Automated SMS Spam Detection Using NLP Techniques](https://github.com/kczymchok/Deep_learning_Spam_detector)

AT&T aims to tackle spam messages by developing an automated spam detector. The goal is to create a model that flags spam messages based solely on SMS content using a provided dataset.The deliverable includes a notebook with preprocessing steps, deep learning model training, and performance evaluation.

<!--- ------------------------------------------------------------------------------------------------------------------------------------------------------ -->
<!--- -- Skills Section ------------------------------------------------------------------------------------------------------------------------------------ -->
<!--- ------------------------------------------------------------------------------------------------------------------------------------------------------ -->


## Skills

| Category             | Skills        |
|----------------------|---------------|
| **Languages**        | ![Python](https://img.shields.io/badge/Python-00599C?style=for-the-badge&logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-00599C?style=for-the-badge&logo=sql&logoColor=white) |
| **Frameworks/Libraries** | ![Keras](https://img.shields.io/badge/Keras-9F000F?style=for-the-badge&logo=keras&logoColor=white) ![Scikit-Learn](https://img.shields.io/badge/Scikit-Learn-FF6700?style=for-the-badge&logo=scikitlearn&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-FFFFFF?style=for-the-badge&logo=tensorflow&logoColor=orange) ![Pandas](https://img.shields.io/badge/Pandas-FFFFFF?style=for-the-badge&logo=pandas&logoColor=red) ![Numpy](https://img.shields.io/badge/Numpy-FFFFFF?style=for-the-badge&logo=numpy&logoColor=blue) ![Plotly](https://img.shields.io/badge/Plotly-000000?style=for-the-badge&logo=plotly) ![Matplotlib](https://img.shields.io/badge/Matplotlib-FFFFFF?style=for-the-badge&logo=matplotlib&logoColor=grey) ![Seaborn](https://img.shields.io/badge/Seaborn-FFFFFF?style=for-the-badge&logo=seaborn&logoColor=blue) |
| **API Development**  | ![FastAPI](https://img.shields.io/badge/FASTAPI-1B8A6B?style=for-the-badge&logo=fastapi&logoColor=white) |
| **Web Scraping**     | ![Selenium](https://img.shields.io/badge/Selenium-12AD2B?style=for-the-badge&logo=selenium&logoColor=white) ![Beautiful Soup](https://img.shields.io/badge/Beautiful%20Soup-FFFFF?style=for-the-badge&logo=beautifulsoup&logoColor=black) |
| **Data Engineering** | ![Airflow](https://img.shields.io/badge/Airflow-990012?style=for-the-badge&logo=apache-airflow&logoColor=white) ![Kafka Confluent](https://img.shields.io/badge/Kafka%20Confluent-000000?style=for-the-badge&logo=apachekafka&logoColor=white) |
| **Database**         | ![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/Postgresql-FFFFFF?style=for-the-badge&logo=postgresql&logoColor=blue) |
| **Cloud Platforms**  | ![AWS S3](https://img.shields.io/badge/AWS%20S3-006400?style=for-the-badge&logo=amazonaws&logoColor=white) ![AWS Redshift](https://img.shields.io/badge/AWS%20Redshift-4169E1?style=for-the-badge&logo=amazonaws&logoColor=white) |
| **Deployment**       | ![Heroku](https://img.shields.io/badge/Heroku-430098?style=for-the-badge&logo=heroku&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-FFFFFF?style=for-the-badge&logo=docker&logoColor=blue) ![Docker Compose](https://img.shields.io/badge/Docker%20Compose-000000?style=for-the-badge&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-306EFF?style=for-the-badge&logo=kubernetes&logoColor=white) ![MLflow](https://img.shields.io/badge/MLflow-FFFFFF?style=for-the-badge&logo=mlflow&logoColor=blue) ![Streamlit](https://img.shields.io/badge/Streamlit-FFFFFF?style=for-the-badge&logo=streamlit&logoColor=red) |
| **Versioning**       | ![GitHub](https://img.shields.io/badge/GitHub-000000?style=for-the-badge&logo=github&logoColor=white) ![Git](https://img.shields.io/badge/Git-E44C30?style=for-the-badge&logo=git&logoColor=white) |


  

<div align="center">
  <br>
  <a href="https://www.linkedin.com/in/kevin-chok/"><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:kevin.chok@outlook.com"><img src="https://img.shields.io/badge/Send Email-c71610?style=for-the-badge&logo=email&logoColor=blue" /></a>
  
</div>


