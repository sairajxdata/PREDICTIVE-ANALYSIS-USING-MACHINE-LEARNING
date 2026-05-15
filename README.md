# PREDICTIVE-ANALYSIS-USING-MACHINE-LEARNING

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: SAIRAJ JANARDAN PATIL

*INTERN ID*: CTIS8472

*DOMAIN*: DATA ANALYTICS 

*DURATION*: 6 WEEKS

*MENTOR*:  NEELA SANTHOSH KUMAR

*DESCRIPTION*: Of Project Predictive Analysis Using Machine Learning

This practical demonstrates the implementation of a Predictive Analysis system using Machine Learning to estimate house prices based on various housing features. The project is developed in Python using popular data science and machine learning libraries such as Pandas, NumPy, Matplotlib, and Scikit-learn. The main objective of this practical is to build a regression model capable of predicting house prices accurately by learning patterns from historical housing data.

The dataset used in this project is the House Prices dataset (train.csv), which contains multiple numerical and categorical attributes related to residential properties, such as lot size, number of rooms, quality ratings, year built, and many other housing characteristics. The target variable for prediction is SalePrice, which represents the selling price of a house.

The practical begins with importing the required Python libraries for data preprocessing, visualization, feature selection, model training, and evaluation. The dataset is loaded using the Pandas library, and initial exploratory operations such as viewing the first few rows and checking missing values are performed. Since real-world datasets often contain incomplete information, missing values are handled carefully. Numerical columns are filled using the median value of each column, while categorical columns are filled using the mode (most frequent value). This preprocessing step ensures data consistency and improves model performance.

After handling missing values, categorical features are converted into numerical form using Label Encoding. Machine learning models cannot process text-based categorical data directly, so encoding transforms labels into numerical representations that can be understood by the model.

The dataset is then divided into input features (X) and target output (y). Unnecessary columns such as Id are removed because they do not contribute to prediction accuracy. To improve model efficiency and reduce dimensionality, feature selection is performed using SelectKBest with the f_regression statistical method. This step selects the top 15 most important features that have the strongest relationship with the target variable (SalePrice). Feature selection helps reduce noise, decreases computational complexity, and improves predictive performance.

Next, the dataset is split into training and testing sets using train_test_split. The training set is used to train the machine learning model, while the testing set is used to evaluate prediction performance on unseen data. Feature scaling is then applied using StandardScaler, which standardizes the data by transforming it to have zero mean and unit variance. Scaling improves the performance of many machine learning algorithms and ensures that all features contribute equally.

The machine learning model used in this practical is Linear Regression, a supervised learning algorithm commonly used for predictive analysis and continuous value prediction. The model learns the relationship between housing features and house prices during training. After training, predictions are generated for the test dataset.

To evaluate model performance, several regression metrics are calculated, including:

Mean Squared Error (MSE) – measures average squared prediction error.
Root Mean Squared Error (RMSE) – represents prediction error in original units.
R² Score – indicates how well the model explains the variance in house prices.

Finally, a scatter plot of actual versus predicted house prices is generated using Matplotlib. This visualization helps analyze how closely the predictions match the real values.

Overall, this practical provides a complete workflow for predictive analytics using machine learning, including data preprocessing, feature engineering, model building, evaluation, and visualization. It demonstrates how machine learning techniques can be effectively used for real-world price prediction problems.
