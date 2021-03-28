# Spark ML Flowers Classification :
___

The aim of this project is to use _Machine Learning_ on a BigData context.

The problem treated is a classic images classification problem : through the <code>SparkFlowersClassification.py</code> algorithm, I applied some basic preprocessing, did some data exploration, and finally implemented and evaluated the performance of some classic machine learning algorithms.

This algorithm was implemented as an academic project for the BigData lecture given by <a href="https://github.com/jgratien">Prof.Jean-Marc Gratien</a>.

the data used to train and test the different models is the  <a href="https://archive.ics.uci.edu/ml/datasets/iris">Iris Flowers</a> dataset.
 
> #### Execution :
___

The data is uploaded to the hadoop env and the used, please change the data <b>path</b> to yours for any future use.

This machine learning pipeline can be executed as such :

<center> <code> python SparkFlowersClassification.py [classifier]</code> </center>

where _classifier_ can be : 
    
    - lr : Linear Regression
    - dt : Decision Tree
    - rf : Random Forest

> #### Requirements :
___
- Python v > 3.6 
- hadoop env v > 2.10
- Spark env v > 3.7
- pyspark

___
___
> #### Author : Benhari Abdessalam
> #### Date : 25/02/2021
