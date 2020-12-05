# Neural_Network_Charity_Analysis
Using machine learning and neural networks to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

## Data Preprocessing

What variable(s) are considered the target(s) for your model? 
- The target variable for the model is the "IS_SUCCESFUL" since we want the model to determine if the applicants will be succesful if funded by Alphabet Soup

What variable(s) are considered to be the features for your model?
- The features variables are everything except for the target, and the name and EID columns

What variable(s) are neither targets nor features, and should be removed from the input data?
- The name and EID columns should be removed. In the opitmization I also removed status to reduce the noise within the model

## Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?
- I started with 10 neurons in the first layer and 8 in the following layer. After I ran it and saw the model was performing at 71% I went and increased the the number of neurons and ran it again. I added up to 30 in one layer and 20 in the second layer and 12 in the third layer and the results were around 73% accuracy. 

Were you able to achieve the target model performance?
- I wasn't able to achieve the models performance.

What steps did you take to try and increase model performance?
- I removed some columns to try to remove noise. That didn't work. The next few steps I took was to add a 3rd layer, add more neruons to each layer, and played with the activation functions and tested different combinations of RELU, Sigmoid, etc. 

