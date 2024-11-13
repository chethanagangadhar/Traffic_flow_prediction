# Traffic Flow Prediction

## Project Overview
This project predicts traffic flow based on historical data, analyzing vehicle counts (cars, bikes, buses, trucks), time, and day of the week. It identifies traffic patterns to support urban mobility, reduce congestion, and optimize traffic control strategies, ultimately contributing to sustainability goals by minimizing emissions and fuel consumption.

## Key Data Insights
- **Peak Hours**: Traffic peaks during morning and evening rush hours, especially for cars and bikes.
- **Vehicle Patterns**: Cars dominate traffic volume, while trucks are consistently lower and more stable.
- **Traffic Situations**: Congestion increases with truck traffic, affecting overall traffic conditions.

## Model and Evaluation
- **Model**: A Random Forest Classifier predicts traffic situations, achieving high accuracy in identifying congested periods.
- **Key Features**: CarCount, BikeCount, Day of the Week, and Hour were most influential in predicting traffic flow.
- **Evaluation**: Confusion matrix and classification report metrics (precision, recall, F1-score) were used to validate model performance.

## Conclusion
The model provides valuable insights for managing traffic, helping city planners adjust traffic signals and schedules to alleviate congestion. By predicting traffic patterns, the project supports smart city initiatives, enhancing urban mobility and reducing environmental impacts.
