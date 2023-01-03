# deep-learning-challenge

# Overview
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With my knowledge of machine learning and neural networks, I will create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

# Results

* Data Preprocessing

  * Our target variable is the IS_SUCCESSFUL column
  * The features for our model are APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT
  * The EIN and NAME columns were removed because they are neither targets nor features

* Compiling, Training, and Evaluating the Model

  * My first model includes:
    * A first hidden layer with 8 nodes and activation function relu
    * A second hidden layer with 8 nodes and activiation function relu
    * An output layer with activation function sigmoid

  * I was unable to achieve the target model performance of 75%
  ![image](https://user-images.githubusercontent.com/106372646/210303705-689b852e-85e3-4639-a4b3-50d39bcb8ed9.png)


  * I created another model using the following:
    * A first hidden layer with 5 nodes and activation function relu
    * A second hidden layer with 5 nodes and activiation function relu
    * An output layer with activation function sigmoid
    * Still unable to achieve the target model performance of 75%
   ![image](https://user-images.githubusercontent.com/106372646/210303908-cf501815-8af0-4b1c-aa3c-6ae1e9a3d611.png)
  
# Summary
I spent some time toggling with different nodes and epochs and was still unable to achieve the target model performance between the 2 models I created. I believe if I invest more time in testing different activation functions, adding/removing layers and finding the right number of nodes, I could probably get to the targeted model performance of 75%.
