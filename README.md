# deep-learning-challenge
# Overview:
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With the knowledge of machine learning and neural networks, the features in the provided dataset will be used to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.
Alphabet Soup’s business team have provided a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. 

# Results:
# Data Preprocessing

* What variable(s) are the target(s) for your model?
* The target variable is the 'IS_SUCCESSFUL' column from application_df
![](Deep%20Learning%20Challenge/Images/Targetandfeatures.jpg)

* What variable(s) are the features for your model?
* The feature variables are every other column from application_df --> this was defined by dropping the 'IS_SUCCESSFUL' column from the original dataframe

* What variable(s) should be removed from the input data because they are neither targets nor features?
* Both 'EIN' and 'NAME' columns were dropped/removed, because they were neither targets nor features for the dataset.
![](Deep%20Learning%20Challenge/Images/DropColumns.jpg)

# Compiling, Training, and Evaluating the Model:

* How many neurons, layers, and activation functions did you select for your neural network model, and why?
* In the first attempt, i used 10 hidden_nodes_layer1 and 5 hidden_nodes_layer2 -- these are the random guesses from which to iterate upon in the second try.
![](Deep%20Learning%20Challenge/Images/firstmodel.jpg)

* Were you able to achieve the target model performance?
* I could achieve only 72% model accuracy.
![](Deep%20Learning%20Challenge/Images/firstmodelaccuracy.jpg)

* What steps did you take in your attempts to increase model performance?
* I have added more layers, additional hidden nodes, and switched up the activation functions associated with each layer in an attempt to achieve higher model accuracy. However, the target model accuracy didn't improve much.

# Summary:
Overall, the model was 73% accurate in predicting the classification problem. While using a model with greater correlation between input and output would likely result in higher prediction accuracy. This could be achieved by more pre-processing of data, as well as by using a model with different activation functions until higher accuracy is achieved.


