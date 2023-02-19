# Various sampling techniques on Imbalanced Dataset
Credit card fraud detection data is an imbalanced data set with two classes 0 and 1. 0 class means no fraud and 1 means fraud. 

<img width="380" alt="image" src="https://user-images.githubusercontent.com/65918628/219943483-eee58097-017e-4d46-8b46-275d1bf48485.png">

We Can either use oversampling or undersampling to make our data balanced. Here we used Oversampling (SMOTE)

<img width="379" alt="image" src="https://user-images.githubusercontent.com/65918628/219943645-45671bda-a718-4f9c-a59c-f9e6f55b16a5.png">


5 different sampling techniques were used to train 6 different classification models (Kneighbors,Bernoulli,logistic,Decision,Random,SVC). 

Simple Random Sampling: Each data point in the dataset has an equal probability of being selected in the sample.

Systematic Sampling: Every mth element in the population is selected for the sample.

Stratified Sampling: The population is divided into subgroups (strata) based on a specific characteristic, and samples are taken from each stratum in proportion to the population.

Cluster Sampling: The population is divided into clusters, and a sample of clusters is randomly selected. Then, all members of the selected clusters are included in the sample.

Normal : The total population is split into train and test data directly 

Sample size formulas were used to decide sample size. 
Efficient modelling was done using Grid Search. Testing was done on the remaining data set.

Final output

<img width="350" alt="image" src="https://user-images.githubusercontent.com/65918628/219943726-f0eaaf03-f578-4492-bf13-0c951b030249.png">

Best models for all sampling  method: 
In this case random forest is the best model for all

<img width="355" alt="image" src="https://user-images.githubusercontent.com/65918628/219943755-12bbccac-913e-488a-bac1-9a1dd44c98bf.png">
