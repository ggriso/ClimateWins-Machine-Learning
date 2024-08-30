# Weather Conditions & Climate Change with ClimateWins

Performing optimization techniques - gradient descent - and supervised machine learning algorithms like K-Nearest Neighbor (KNN), Decision Tree, and Artificial
Neural Network (ANN) to identify the most effective approach to predict daily weather conditions that are favourable for outdoor activities and everyday life 
(so-called "pleasant" weather).

### Context

ClimateWins is a nonprofit organization interested in addressing the challenges posed by climate change, particularly the increase in extreme weather events across mainland Europe in the last 10 to 20 years.
ClimateWins believes that advanced tools, such as machine learning, could be pivotal in predicting and preparing for such weather extremes.
By leveraging weather data from the past century, ClimateWins hopes to develop a predictive model that could offer insights into future weather patterns.

Key questions:
• How is machine learning used in weather forecasting?
• What ethical concerns surround the use of ML and AI?
• What are the historical extremes in temperature?
• Can machine learning be employed to predict weather conditions on specific days?

### Data Source

The [data set](https://s3.amazonaws.com/coach-courses-us/public/courses/da-spec-ml/Scripts/A1/Dataset-weather-prediction-dataset-processed.csv) is based on 
weather observations from 18 different weather stations across Europe, which contain data ranging from 1960 to 2022.
Recordings exist almost daily with values such as temperature, wind speed, snow, global radiation, and more.
This data is collected by the [European Climate Assessment & Data Set project](https://www.ecad.eu/).
An [additional data set](https://images.careerfoundry.com/public/courses/da-spec-ml/Scripts/A1/Dataset-Answers-Weather_Prediction_Pleasant_Weather.csv) was employed
to train the ML models. This data set categorizes each day as either 1 or 0, indicating whether the weather was considered pleasant or not.

### Project Hypotheses

1. Europe has had a statistically significant increase in average annual temperatures in the last two decades.
2. Machine learning models trained on historical data can accurately predict future extreme weather events.
3. Supervised learning models are particularly effective for forecasting whether pleasant weather conditions will occur on a given day.

### Project Folder Structure

The project files are organized into the following folders:
- **01 Project Management:** includes the Project Brief.
- **02 Data:** divided into two subfolders:
  1. Original Data: unscaled weather data + pleasant weather prediction data
  2. Prepared Data: scaled weather data
------ MAY BE OMITTED FROM THE REPOSITORY FOR SPACE-SAVING PURPOSES ------
- **03 Scripts:** contains Jupyter notebooks with the corresponding code.
- **04 Analysis/Visualizations:** holds relevant visuals.
- **05 Sent to Client:** contains a pdf presentation to ClimateWins stakeholders.
