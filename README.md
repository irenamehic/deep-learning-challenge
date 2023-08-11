# deep-learning-challenge

Overview of the analysis: he nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup

Results: 

Data Preprocessing

 - What variable(s) are the target(s) for your model?
     The target for our model is to predict IS_SUCCESSFUL, if the money used effectively by the organization/group.
- What variable(s) are the features for your model?
    EIN and NAME—Identification columns
  APPLICATION_TYPE—Alphabet Soup application type
  AFFILIATION—Affiliated sector of industry
  CLASSIFICATION—Government organization classification
  USE_CASE—Use case for funding
  ORGANIZATION—Organization type
  STATUS—Active status
  INCOME_AMT—Income classification
  SPECIAL_CONSIDERATIONS—Special considerations for application
  ASK_AMT—Funding amount requested

What variable(s) should be removed from the input data because they are neither targets nor features?
  EIN and NAME—Identification columns
Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
  
Were you able to achieve the target model performance?
  No not quite, there wasn't much of a change in accuracy. it was around 73%
What steps did you take in your attempts to increase model performance?
  I removed another column, adjusted the input features, and added 3 hidden layers.
Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
  I think I could improve one some of the data pre-proceesing and maybe a different type of model, as well as the neruons/layers.
