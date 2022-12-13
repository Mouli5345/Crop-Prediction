# Crop Prediction<br/>
### About<br/>
This application, when given the soil conditions, forecasts the ideal crop for Indian soil. The purpose of this application was to assist rural government agencies in increasing the productivity of farmers in those areas. The best crop that can grow in a particular soil can be predicted using machine learning algorithms in this web application.

### Dataset<br/>
The dataset used for this project is the **Crop Recommendation Dataset** provided by ***Atharva Ingle*** on Kaggle. The link is given below:<br/>
https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset<br/>
This dataset was built by augmenting datasets of 
rainfall, climate and fertilizer data available for India. This 
dataset consists of the following data fields: 
- N - ratio of Nitrogen content in soil 
- P - ratio of Phosphorous content in soil 
- K - ratio of Potassium content in soil 
- temperature - temperature in degree Celsius 
- humidity - relative humidity in % 
- pH - pH value of the soil 
- rainfall - rainfall in mm <br/>
The collection includes roughly 2200 items for crops that were recorded along with specific soil conditions.

### Building machine learning model
The Random Forest Classifier is the machine learning algorithm that was utilised to create this model. The Random Forest Classifier model's parameters are 100 n estimators with 
maximum tree depth is 3, the smallest leaf sample is 4, and the random state is 0.
