# DTEC

**Improving Recommender Systems via a Dual Training Error based Correction Approach 


This code (code.zip) is a simple (not speed optimized)  implementation of  DTEC method proposed in [1]. 

You can find more details in 
https://sites.google.com/site/costaspanagiotakis/research/scor-dtec 

Files: 
   runRS_DTEC.m script of implemetation of the DTEC approach [1] with an RS 
   getRS_DTEC.m: function that implements DTEC approach [1]  
   runSCOR_DTEC.m: script of implemetation of the DTEC with SCoR [2] 	

The datasets and code can be found in 
https://sites.google.com/site/costaspanagiotakis/research/scor-dtec 


Short description: 
We propose a method to improve the prediction performance of recommender systems via a
Dual (user and item) Training Error based Correction approach (DTEC). The proposed method is
applied to the Synthetic Coordinate Recommendation system (SCoR) (Papadakis, Panagiotakis
and Fragopoulou (2017)) and to other three state-of-the-art systems. Initially, a recommender
system is used to provide recommendations for users and items. Subsequently, we introduce a
second stage, after initial execution of the recommender system, that improves its predictions
taking into account the error in the training set between users and items and their similarity. These corrections can be performed from both user and item viewpoints, and finally a dual system is proposed that efficiently combines both corrections. DTEC computes a model that makes zero the recommendation error in the training set, and then applies it on the test set to improve the rating predictions. The proposedDTEC approach is applicable to any model-based recommender system with positive training error, potentially increasing the accuracy of the recommendations.

We will appreciate if you cite our papers in your work: 

[1] C. Panagiotakis, H. Papadakis, A. Papagrigoriou and P. Fragopoulou, Improving Recommender Systems via a Dual Training Error based Correction Approach,   Expert Systems with Applications, 2021

[2] H. Papadakis, C. Panagiotakis and P. Fragopoulou, SCoR: A Synthetic Coordinate based Recommender System, Expert Systems with Applications, vol. 79, pp.8-19, 2017.  
