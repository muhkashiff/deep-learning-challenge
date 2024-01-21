# deep-learning-challenge
## Overview:
    Purpose of this analysis is to create a tool for the nonprofit Organization Alphabet Soup<br>
    by using Machine Learning and Neural Network Technique so they can make a decision about<br>
    the potential future applicants to either approve or reject the application.<br>
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
      <li>Model 2 parameters:</li>
          No. of Hidden layers: 2<br>
          No. of nodes: First layers: 90, second & third :40, output layer:1<br>
          No. of epochs: 100<br>
          Activation first layer: relu<br>
      <li>Model 3 parameters:</li>
          No. of Hidden layers: 3<br>
          No. of nodes: First layers: 80, second & third :30, output layer:1<br>
          No. of epochs: 200<br>
          Activation first layer: sigmoid<br>
</ul>
