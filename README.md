# Multivariate-Regression-Model
We are performing Multivariate Linear regression model on boston housing dataset which would be attached in the repository using SAS enterprise Miner.
The input variables are 
- Age
- Black
- Crim
- Dis
- Indus
- lstat
- nox
- ptratio
- rm
- tax
- zn

And the Target variable is :
- Medv

The nodes involved are as follow:
1. File import node 
2. Data partition node
    - Training data set - 50%
    - Validation data set- 40%
    - Test data set - 10%
 3. Regression Model node
    - Input Coding - GLM
    - Regression type(Linear Regression)
    - Selection Method
       - Forward Selection
       - Backward Selection
       - Stepwise Selection
            
<p align ='center' width ='80%'>
    <img width ="80%" src= "https://user-images.githubusercontent.com/74041244/158021006-c9377626-eb2b-4a60-9613-9432a497e923.png"  alt="centered image" />
</p>
 

