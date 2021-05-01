# Fertilizer-Prediction
Predicting the type of fertilizer to be used depending on the crop type and soil type
Dataset is taken from Kaggle. \
Link : https://www.kaggle.com/gdabhishek/fertilizer-prediction

## Variable Details:
Dataset consists of 8 variables where 7 variables are considered for predicting output variable. The details of Variable is given Below
1. N (Nitrogen) : Nitrogen content in the soil. Nitrogen is really important for plant growth (structure), plant food processing (metabolism), and the creation of chlorophyll. Without enough nitrogen in the plant, the plant cannot grow taller, or produce enough food (usually yellow).
2. P (Phosphorus) : Phosphorus content  in the soil. Phosphorus primary role in a plant is to store and transfer energy produced by photosynthesis for use in growth and reproductive processes. Soil P cycles in a variety forms in the soil 
3. K (Potassium) : Potassium content in the soil. Potassium is an essential nutrient for plant growth.
4. Temperature : Temperature in degree censius. High temperatures affect plant growth in numerous ways. The most obvious are the effects of heat on photosynthesis, in which plants use carbon dioxide to produce oxygen, and respiration, an opposite process in which plants use oxygen to produce carbon dioxide.
5. Humidity : Relative humidity in %. When conditions are too humid, it may promote the growth of mold and bacteria that cause plants to die and crops to fail, as well as conditions like root or crown rot. Humid conditions also invite the presence of pests, such as fungus gnats, whose larva feed on plant roots and thrive in moist soil.
6. Soil Type : 
7. Crop Type : \
Finally,
8. Label : This is the output variable which contains 22 unique values i.e., 22 different crops and they are 
    1. '10-26-26'
    2. '14-35-14'
    3. '17-17-17'
    4. '20-20'
    5. '28-28'
    6. 'DAP'
    7. 'Urea' 
 
Exploratory data analysis carried out to fetch insights from the data.

## Algorithm :
Only three algorithms are used to predict the output. They are *Logistic Regression* and *Random Forest*.\
1. Accuracy of the model using Logistic Regression is 90%.
2. Accuracy of the model using Random Forest Classifier is 98%.
*Random Forest Classifier* is used for development of model.

## Deployment : 
I have used *flask* library to create the application.\
The application is deployed in *Google Cloud Platform*.
App URL : https://fertitilizer-prediction.el.r.appspot.com/
