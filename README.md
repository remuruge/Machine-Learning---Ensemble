# Machine-Learning---Ensemble

I. Prepare data analysis:
1. Load the data into Dataframe. The dataframe should have data and column description
1a. Univariate analysis:
data types and description of the independent attributes which should include (name, meaning, range of value observed, central values, std deviation, quartiles, analysis of the body of distributions/tails, missing values, outliers).
1b. Multivariate analysis:
Bi-variate analysis between the predictor variables and between the predictor variables and target column. Comment on your findings in terms of their relationship and degree of their relationship if any. Presence of leverage points. Visualise the analysis using boxplots and pairplots, histograms or density curves. Select the most appropriate attibutes.  
2. Ensure the attributes types are correct. If not, take appropriate actions
3. Transfor the data - scale/normalise the data if required.
Address data challenges like data pollution, outliers and missing values.
4. Create the training set and test set in 70:30 ratio

II. Create ensemble model:
1. Write python code using scikitlearn, pandas, numpy, and others in jupyter notebook to train and test the ensemble model.
2. First create a model using standard classification algorithms   the model performance
3. Use appropriate algorithms and explain why that algorithms in the comment lines.
4. Evaluate model. Use confusion matrix to evaluate class level metrics i.e. Precision and recall. Also reflect the overall score of the model.
5. Advantages and Disadvantages of the algorithms.
6. Build the ensemble models and compare the results with the base model. Note. Random forest can be used only with the Decision Tress.

III. Tuning the model:
1. Discuss some of the key hyper parameters available for the selected algorithm. What values did you initalise these parameters to.
2. Regularisation techniques used for the model.
3. Range estimate at 95% confidence for the model performance in production.

Objective:
Build the model that will help the marketing team directly identify potential customers who are relatively more likely to subscribe term deposits and thus increase their hit ratio. - uci dataset.
