# Multinomial Text based Classifier
Implementation of multinomial text based classifier

This notebook is my implemantation of a text-based classifier. We try to predict what the variety(category) of a wine will be based on a text description(review_description) Since this is my first attempt at a NLP-esque problem, this is a work in progress.
The current version of the model gives a fairly accurate score of 0.70. But I hope to improve it in the future.
![image](https://user-images.githubusercontent.com/58383734/81398350-ae865980-9146-11ea-864a-3b2ae5eda5cf.png)

In this implementation, we skip predictor variables other than the *review_description* to ease up the resources and because this is the result of a few hours of one night. I'll try to come back and improve the model.

## Prerequisites
*Note: I ran the codes on Google Colab, because well it gives you access to a 25GB RAM machine and I really needed that power to crunch the term frequency vectors.*

Other than the pre-installed libraries in Jupyter notebooks, we don't need to install any new libraries.
* pandas
* numpy
* scikit-learn
* matplotlib
* seaborn




License
------
Apache 2.0 
