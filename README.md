# Time-Aware-Music-Recommedation-System-Lastfm

#### Dataset
Sample dataset files have been provided in the "/datasets" folder.

Dataset link: 
https://www.kaggle.com/neferfufi/lastfm


#### Major Dependencies:
The following tools and packages need to be installed:
Spark, Keras, Python 3.6

#### Minor Dependencies:
Anaconda Navigator, Jupyter Notebook (to run .ipynb files)

#### To install new packages in Anaconda, we need to run the below command:
 conda install -c conda-forge <package_name> 
 eg:  conda install -c conda-forge implicit 

Many of the packages such as Numpy, scipy, pandas are consdered the basic requirements and are included in the Anaconda Navigator base package. As such, we assume that these basic packages are installed in the system.

#### Steps to follow to run the code:
1) Install the following packages:
   datetime, surprise ,sklearn, implicit, keras, itertools,
   findspark,pyspark, mllib.recommendation.ALS, mllib.recommendation.MatrixFactorizationModel, 
   mllib.recommendation.Rating   
2) Change the path of the dataset file from where its reading
3) Run the program using Anaconda Jupiter notebook

#### Folder structure
/datasets: contains sample dataset files

/html: contains the .html files of the ipython notebooks

Presentation and Report is located at the root folder itself.

#### Algorithms used:

1) Surprise SVD
2) Regression with Keras
3) ALS (Alternating Least Squares)
4) Bayesian Personalised Ranking
5) Logistic Regression
6) KNN  Classifier
