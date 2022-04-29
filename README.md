# Defining-new-estimator

In this project, I am going to define a new estimator. It is the KNN model with different similarity metrics and prediction computing. Note that, the main goal here is just to see how was can define new estimators. So, I did not do data cleaning. At the end, you can use GridSearchCV to find the best parameters. your parameters can be like the following.
parameters={'n_neighbors':[100,200],'metric':['cosine','corrolation','Adjusted'], 'pred':['weighted_sum']}
I did this project by reviewing some other projects and reading some papers. Hence, it is what I have learned about difining estimators.
