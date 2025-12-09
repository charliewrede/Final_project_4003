# Machine Learning and Spatial Data Final Project
This is the repository for our final project in GEOG 4003 machine learning and spatial data. 

The model performs multi-output regression, predicting a continuous value for each venue category. These predictions are then converted into a probability distribution, similar to a SoftMax, for every location, day, and hour combination. We use an XGBoost-based model in SciKit-Learn’s MultiOutputRegressor to handle the multi-output regression problem, using location and time features to estimate the likelihood of visits to each venue category.
