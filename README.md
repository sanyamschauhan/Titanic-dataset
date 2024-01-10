# Titanic-dataset
 
In this Python code snippet, I conducted an initial exploration and preprocessing of the Titanic dataset. After loading the data, I visualized missing values and examined the age distribution across passenger classes using a heatmap and boxplot, respectively. To enhance the dataset's completeness, I imputed missing age values based on the passenger class.

Following data preparation, I selected pertinent features and explored their relationships through a correlation heatmap. Moving on to model preparation, I employed Label Encoding to encode categorical variables, specifically 'Sex.' The dataset was then split into features (X) and the target variable (y), and further divided into training and testing sets using train_test_split.

While the code includes comments mentioning various machine learning models such as Logistic Regression, SVM, Decision Tree, and RandomForest, these models are presently commented out. The model training section is incomplete, with predictions stored in the t_predict variable. The accuracy of the model is evaluated using the accuracy_score function.

To make the code fully functional, uncomment and execute the relevant model training section, selecting an algorithm (e.g., classifier) for training. The accuracy score will then quantify the model's performance on the test set.

This code mirrors a standard machine learning pipeline, encompassing data preprocessing, feature engineering, model training, and evaluation. Depending on specific goals, one can experiment with uncommenting different algorithms to identify the most suitable one for the dataset and prediction task.
The accuracy scores for the following models with test size= 0.25 and random_state=10
logistic Regression Model - 0.8295964125560538
SVM model('rbf','linear')- 0.7219730941704036 | 0.8251121076233184
Decision Tree - 0.8161434977578476
RandomForest(n_estimator= 100, random_state=50) - 0.8385650224215246 
