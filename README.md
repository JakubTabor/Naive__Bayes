# Naive__Bayes
# I have "X" and "y" prepared, so I can import "train_test_split" and get "train" "test" set
# Then I make "feature scaling", so I import "StandardScaler" and prepare "X_train" """X_train  = sc.fit_transform(X_train)""" 
# And "X_test """X_test = sc.transform(X_test)"""
# Next from "sklearn.naive_bayes" import "GaussianNB" and train my classifier """classifier.fit(X_train, y_train)"""
# I also use my classifier to prepare "y_pred" """y_pred = classifier.predict(X_test)"""
# Now I can import "confusion_matrix" and put into my "y_test" and "y_pred" """cm = confusion_matrix(y_test, y_pred)"""
# And get score """accuracy_score(y_test, y_pred)""", I look at visualizations of my results
