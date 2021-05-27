# Population Segmentation Using SageMaker

### Table of Contents

1. [Libraries](#Libraries)
2. [Project Description](#ProjectDescription)
3. [File Description](#FileDescription)
4. [Analysis](#Analysis)
5. [Licensing, Authors, and Acknowledgements](#Licensing)


## Libraries <a name="Libraries"></a>
* pandas
* AWS SageMaker
* Scikitlearn

## Project Description <a name="ProjectDescription"></a>
As human needs evolve, busineses need to grow and evolve. Marketing strategies whether for politic, business or healthcare needs to be specific and targetted. The needs of a young unmarried college graduate, a 45 year old family man, a single mom who is a lawyer are all different. Segmanting the population according to demographics makes you able to create specific selliing points which are more precise. 
Population segmentation is a type of analysis that allows us to separate populations into subgroups so that we can better assess each group’s wants, needs, and health priorities. In this project we use US Census data from different counties.
Using PCA and K means clustering we first use unsupervised machine learning to understand the different clusters in the group. Then use supervised learning

## File Description <a name="FileDescription"></a>
There are three main folders:

1. data
    - us census data provided by aws
     
## Analysis <a name="Analysis"></a>
The data science workflow has 4 main steps:
1. Loading the data from Amazon S3
2. Exploratory data analysis (EDA) - Data cleaning and exploration
        Cleaning the data
        Visualizing the data
        Feature engineering
3. Data modelling
        Dimensionality reduction
        Accessing the PCA model attributes
        Deploying the PCA model
        Population segmentation using unsupervised clustering
4. Drawing conclusions from our modelling
        Accessing the KMeans model attributes

## Licensing, Authors, and Acknowledgements <a name="Licensing"></a>
Thanks to Udacity for the exercise.









