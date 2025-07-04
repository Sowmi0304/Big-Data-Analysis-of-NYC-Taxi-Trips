# Big-Data-Analysis-of-NYC-Taxi-Trips

This project uses the NYC Taxi Trip Duration dataset and performs large-scale data analysis and regression modeling using **PySpark**. It includes data cleaning, feature engineering, and prediction using ensemble models like **Random Forest** and **Gradient Boosted Trees**.


## Technologies Used
- Python 3.10
- PySpark (Spark MLlib)
- Pandas, Matplotlib
- Jupyter Notebook


##  Dataset
- **Source**: [NYC Taxi Trip Duration - Kaggle](https://www.kaggle.com/datasets/parisrohan/nyc-taxi-trip-duration)
- Features: pickup/dropoff location, date-time, passenger count, trip duration, etc.


##  Data Processing
- Removed missing values and duplicates
- Calculated trip distance using the **Pythagorean approximation**
- Engineered features: pickup hour, day of week, speed


##  Models Compared

| Model                   | RMSE (seconds) | R² Score |
|------------------------|----------------|----------|
| Random Forest Regressor | 2991.75        | 0.0296   |
| Gradient Boosted Trees  |  313.93        | 0.7097   |


##  Key Takeaways
- Gradient Boosted Trees outperformed Random Forest with a significant margin
- Feature engineering played a crucial role in improving prediction
- PySpark is highly effective for scalable machine-learning pipelines


## Contributions

- **Sowmya Reddy** – [GitHub: @Sowmi0304](https://github.com/Sowmi0304)  
  EDA, outlier handling, Random Forest modeling, documentation

- **Faizul Shaik** – [GitHub: @faizulgaffar](https://github.com/faizulgaffar)  
  PySpark setup, feature engineering, GBT modeling, evaluation


## Note
This project is solely for academic and portfolio-building purposes. The insights are exploratory and not intended for commercial decision-making.
