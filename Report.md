 # ***Alphabet Soup Report***


## **Overview of the analysis:**
select the applicants for funding with the best chance of success in their ventures.

# **Results:**

**Data Preprocessing**

What variable(s) are the target(s) for your model?

The target variable is the 'IS_SUCCESSFUL' 

--What variable(s) are the features for your model?

The feature variables are every other column from application_df 

--What variable(s) should be removed from the input data because they are neither targets nor features?

Both 'EIN' and 'NAME' columns were dropped cause they were neither targets nor features for the dataset.

Compiling, Training, and Evaluating the Model

--How many neurons, layers, and activation functions did you select for your neural network model, and why?

 8 hidden_nodes_layer1 and 5 hidden_nodes_layer2 

--Were you able to achieve the target model performance?

I was not able to achieve the 75% model the best was 73% 

--What steps did you take in your attempts to increase model performance?

I added more layers, removed more columns, added additional hidden nodes, 

# **Summary:** 
The deep learning model achieved approximately 73% accuracy in addressing the classification problem. To enhance prediction accuracy, utilizing a model that demonstrates stronger correlation between input and output is advisable. This improvement can be accomplished through additional data cleanup and by experimenting with different activation functions in the model, followed by iterative refinements to achieve better accuracy.
