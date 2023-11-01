# WildBluberryPrediction

Wild blueberries, a globally cherished fruit, have seen their yields influenced by various factors, such as clone size, pollinators (honeybees, bumblebees, andrena, osmia), temperature ranges, rainfall, fruit set, fruit mass, and seeds. My latest project delves into the realm of machine learning to forecast wild blueberry yields independently.

This venture involves three potent regressors: CatBoost, RandomForest, and XGBoost Regressor. Leveraging these models, I meticulously analyzed a comprehensive dataset to make precise predictions about wild blueberry yields.

The journey commences with essential steps. I've imported the necessary libraries and conducted a thorough analysis of the dataset using diverse data exploration and visualization techniques. Once the data preprocessing is complete, I've split it into a training set and a testing set. The training set serves as the basis for model training, while the testing set evaluates the model's performance.

The heart of my project is the CatBoost model, which I've personally created and trained using the diligently prepared training dataset. After training, I've deployed the model to predict wild blueberry yields using the testing dataset. The model's performance is assessed through the R2 score, a valuable metric quantifying the proportion of variation in yield predictable from the independent variables.

To enhance my model's accuracy, I've delved into hyperparameter tuning, a crucial step to fine-tune the machine learning model and improve its yield prediction accuracy.
