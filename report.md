# deep-learning-challenge-21
challenge 21 homework
For this part of the assignment, you’ll write a report on the performance of the deep learning model you created for Alphabet Soup.

The report should contain the following:

Overview of the analysis: Explain the purpose of this analysis.

Results: Using bulleted lists and images to support your answers, address the following questions:

Data Preprocessing

What variable(s) are the target(s) for your model?
<The variable is the 'IS_SUCCESSFUL' from application_df>

What variable(s) are the features for your model?
<The feature variables are other column from application_df, and this was defined by dropping the 'IS_SUCCESSFUL' variable from the original data>

What variable(s) should be removed from the input data because they are neither targets nor features?
<The 'EIN' and 'NAME' should be removed from the input data because they were neither targets nor features for the dataset.>

Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
<I used 5 hidden_nodes_layer1 and 5 hidden_nodes_layer2. In case, these were just random guesses from which to iterate upon in the second try.>
 
Were you able to achieve the target model performance?
<The model only can able to achieve the 73% accuracy target.>

What steps did you take in your attempts to increase model performance?
<In case, I added 10 hidden_nodes_layer1 and 10 hidden_nodes_layer2, and 20 hidden_nodes_layer1 and 20 hidden_nodes_layer2, also removed more columns, added additional hidden nodes, and switched up the activation functions associated with each layer.>

Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
<Within this learning model accuracy was around 73%  in predicting the classification problem. Using a model with greater correlation between input and output would likely result in higher prediction accuracy. This could be achieved by doing additional data cleanup up front, as well as by using a model with different activation functions and iterating until higher accuracy is reached. But in this challenge, I added more layers, remove columns and added additional hidden nodes the accuracy no big change still around 73%>
