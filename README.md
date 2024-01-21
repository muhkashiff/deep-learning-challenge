# deep-learning-challenge
## Overview:
    Purpose of this analysis is to create a tool for the nonprofit Organization Alphabet Soup
    by using Machine Learning and Neural Network Technique so they can make a decision about
    the potential future applicants to either approve or reject the application.
## Results:
<ul>
  <li>Data Preprocessing</li>
      Target variable in Data Set is application_df["IS_SUCCESSFUL"]<br>
      Features variable includes anyother columns than application_df["NAME"] and application_df["EIN"]<br>
  <li>Compiling, Training and Evaluating the Model</li>
      New models for optimization were created after creating BINS for for applicaion_df["INCOME_AMT],["APPLICATION_TYPE"],["CLASSIFICATION"]<br>
      <li>Model 1 parameters:</li>
          No. of Hidden layers: 2<br>
          No. of nodes: First layers: 80, second & third :30, output layer:1<br>
          No. of epochs: 100<br>
          Activation first layer: sigmoid<br> 
    <img src="https://github.com/muhkashiff/deep-learning-challenge/blob/main/image1.png" alt="model1"/>
      <li>Model 2 parameters:</li>
          No. of Hidden layers: 2<br>
          No. of nodes: First layers: 90, second & third :40, output layer:1<br>
          No. of epochs: 100<br>
          Activation first layer: relu<br>
    <img src="https://github.com/muhkashiff/deep-learning-challenge/blob/main/image2.png" alt="model2"/>
      <li>Model 3 parameters:</li>
          No. of Hidden layers: 3<br>
          No. of nodes: First layers: 80, second & third :30, output layer:1<br>
          No. of epochs: 200<br>
          Activation first layer: sigmoid<br>
    <img src="https://github.com/muhkashiff/deep-learning-challenge/blob/main/image3.png" alt="model3"/>
    Based on above changes to model, accuracy could not be increased to 75% target.<br>
    In order to increase the model performance, bining parameters were changed, number of neurons<br>
    were increased, activation parameters were changed.<br>
    
</ul>
