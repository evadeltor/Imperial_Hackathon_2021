# Imperial_Hackathon_2021

## Introduction
One of the most damaging effects that climate change is having is on crop yields. Extreme wether is more comon now than years ago, reason for wich due to droughts, floods, high and low temperatures there is a need to model the behaviour that we are experimenting.

## Pipeline
![Pipeline](images/pipeline.png)
### Data Analysis
  #### Normalisation
At first glance, the data in the Yield field dataset (IL_yield.csv) follows an increasing tendency, similarly to an exponential behaviour. Such behaviour could be caused by the population growth over the years, increase of land devoted to agricultural purposes, acquisition of more advanced and specialized machinery (irrigation techniques, parameter modelling with GPS...), the discovery of more optimal harvesting methodologies, among others. Hence, the application of a normalization method to fairly compare the time evolution between the crop yield together with other explanatory variables is required. 
![Timeline](images/timeline_logan.png)
The normalization is carried out following the procedure proposed by “Reference of the paper https://royalsocietypublishing.org/doi/10.1098/rstb.2019.0510”, which also analysed a similar dataset. To carry out the operations, the following formula is used: 
![Timeline](images/normalisation_formula.png)
Where ai,t is the normalized value of the specific county i and year t,  Yi,t is a specific raw value for a county i and a year t, and  i,t is the mean of all the counties’s yields in a specific year t. 
As it can be seen in the next illustration, the right charts are successfully normalized, correcting the exponential tendency of the raw yield data.  
![Timeline](images/Normalisation.png)


