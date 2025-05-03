# FlowChart
  `1) df = pd.read_csv(" ")` </br>
  `2) X,y` </br>
  `3) train, test` </br>
  `4) X_train.isnull().sum() ==> IF there are null values then we have to fill the missing values using Simple_Imputer [from sklearn.impute import SimpleImputer]` </br>
  `5) if X_train has categorical value then we have to convert it into numerical value using Label Encoder [from sklearn.preprocessing import LabelEncoder]` </br>
  `6) To ensure that all features are contributing equally, we have to normalize the dataframe using Standard Scaler [from sklearn.preprocessing import StandardScalar]` </br>
  `7) Model Selection [lr = LinearRegression()]` </br>
  `8) lr.fit(X_train,y_train)` </br>
  `9) score = lr.score(X_test,y_test)` </br>
  `10) print(score)`</br>
  
