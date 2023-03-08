# Airbnb-Price-Prediction-Model
In this machine learning project, the goal was to predict the price of Airbnb listings using two popular tree-based models: XGBoost and Random Forest.

The first step was to collect and preprocess a large dataset of Airbnb listings, including various features such as location, amenities, and size. The data was then split into training and testing sets, with the training set used to train the models and the testing set used to evaluate their performance.

The XGBoost model was trained using a gradient boosting algorithm, which builds a model by iteratively adding decision trees that minimize the loss function. The model was optimized by tuning hyperparameters such as learning rate, maximum depth, and number of trees.

Similarly, the Random Forest model was trained by building multiple decision trees on random subsets of the data, and then aggregating their predictions. Hyperparameters such as number of trees, maximum depth, and minimum samples per leaf were tuned to optimize the model's performance.

Both models were evaluated using common regression metrics such as mean absolute error (MAE) and mean squared error (MSE). The best performing model was then used to predict the prices of new Airbnb listings.

Overall, this machine learning project demonstrated the effectiveness of using tree-based models such as XGBoost and Random Forest for predicting Airbnb prices, and highlighted the importance of carefully tuning hyperparameters to optimize model performance.
