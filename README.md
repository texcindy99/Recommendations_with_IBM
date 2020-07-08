### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python.  The code should run with no issues using Python versions 3.*.

## Project Motivation <a name="motivation"></a>

This is Udacity recommendation system project. I was interestested in using real data from the IBM Watson Studio platform to:

1. Explore the data to understand the number of users, articles, and information about the interactions that take place;
2. Create rank based recommendations by pulling the top articles;
3. Create collaborative filtering based recommendations for a specific user by finding the similar users and pulling their interactived articles that the specific user hasn't seen;
4. Perform SVD matrix factorization on user-item matrix to predict user-item interaction and both training and test data and assess its performance using different number of latent features.
 
## File Descriptions <a name="files"></a>

There is one notebook available here to showcase work related to the above questions. The notebook is exploratory in searching through the data pertaining to the questions showcased by the notebook title.  Markdown cells were used to assist in walking through the thought process for individual steps.  

There are two data files used in the notebook that you can find in the "data" folder. "user-item-interactions.csv" is the data file for user-item interaction. "articles_community.csv" is the data file containing article information.

## Results <a name="results"></a>

The main findings of the code is successfully making collaborative filtering based recommendations for users whose information exists in user_item matrix. For new users, we can make knowledge based recommendation on top interacted articles. We can also predict the user-item interaction and assess the performance on prediction using SVD with different number of latent features. 

## Licensing, Authors, Acknowledgements <a name="licensing"></a>

Must give credit to Udacity and IBM Watson Studio for the data.  You can find the Licensing for the data and other descriptive information at [Udacity](https://www.udacity.com/course/data-scientist-nanodegree--nd025) and [IBM Watson Studio](https://dataplatform.cloud.ibm.com/) websites.  Otherwise, feel free to use the code here as you would like! 
