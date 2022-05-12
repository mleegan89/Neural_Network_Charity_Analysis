# Neural_Network_Charity_Analysis

## Overview of Analysis

The purpose of this analysis was to create a model that would predict whether an applicant would be successful or not if funded by Alphabet Soup. Using over 34,000 data points we hope to be able to derive a model that predicts above 75% accuracy.

## Results

- Data Preprocessing
  - The variables considered the target for our model is "Is Successful"
  - The variables considered to be the features are application type, affiliation, classification, use case, organization, status, income amount, special considerations, ask amount
  - The variables that were dropped from analysis were EIN and Name.
 
- Compiling, Training, and Evaluating the Model
  - For the first attempt we used 2 hidden layers, both relu activation functions
  
 <img width="506" alt="image" src="https://user-images.githubusercontent.com/96085210/168150998-e858eb7e-a35b-427a-85ee-bff27b855e87.png">
  
 - For the first optimization effort we used 3 hidden layers - 2 relu and the last tanh

<img width="509" alt="image" src="https://user-images.githubusercontent.com/96085210/168151288-f8f1f5aa-ee28-4d08-b441-5ec3e60fb93a.png">

- For the second optimization effort we used 3 hidden layers and adjusted the nodes. We also used relu for the first layer, sigmoid for the second layer and tanh for the third layer.

<img width="521" alt="image" src="https://user-images.githubusercontent.com/96085210/168151382-6e55acdc-2dc1-402c-b74e-d3679479f0ff.png">

- For the third optimization effort we used 3 hidden layer, all tanh, and adjusted the amount of nodes.

<img width="507" alt="image" src="https://user-images.githubusercontent.com/96085210/168151511-8067ad00-a60d-4c0d-91ef-f69d8b3b55e6.png">

## Summary

Unfortunately, we were not able to achieve the goal of 75% accuracy. Results listed below:

1st Model

![image](https://user-images.githubusercontent.com/96085210/168151689-88ac1684-b2e4-4785-a69f-895e2f864196.png)

2nd Model

![image](https://user-images.githubusercontent.com/96085210/168151747-9581b050-178f-442d-951e-fc38c0cc34f9.png)

3rd Model

![image](https://user-images.githubusercontent.com/96085210/168151796-21b6f8c9-ffdd-406a-b299-231f4971e4d7.png)

4th Model

![image](https://user-images.githubusercontent.com/96085210/168151834-ffee87f3-0a03-4af1-89b9-38fe51b08b23.png)

I believe in order to have better results we likely will need to begin to start to remove some categories of the data. Some of them may be irrelevant and negatively impacting the models. I would first start by using three categories that I think are most influential and begin to model again. 


