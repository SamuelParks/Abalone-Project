# Predicting the Age of Abalone using Machine Learning and Neural Networks

#### Group NoFloods: 
* Amit Patel
* Daniah Al Bayati
* Roopa Patel
* Samuel Parks
* Steven Lee


Presented on: `August 18, 2020`


- - -

## Introduction
What is an abalone? From Wikipedia, an abalone is a common name for any of a group of small to very large sea snails, marine gastropod molluscs in the family Haliotidae. Determining the age of abalone is typically time consuming - requiring cutting the shell, staining it, then counting the number of rings with a microscope.  We want to see if physical measurements can be used to predict the age.

- - -

## Dataset 
The data for the project comes from the UCI Machine Learning Repository: https://archive.ics.uci.edu/ml/datasets/Abalone

* There are 4,177 rows in the dataset with 8 attributes:
  * 1 Categorical
    * Sex: Values of (M)ale, (F)emale, (I)nfant
  * 6 Continuous:
    * Length (mm): the longest shell measurement
    * Diameter (mm): perpendicular to length
    * Height (mm): with meat in shell
    * Whole Weight (g): whole abalone
    * Viscera Weight (g): gut weight after bleeding
    * Shell Weight (g): after being dried
  * 1 Integer
    * Rings: Note that Age of the Abalone in years = Rings + 1.5 

- - -

## Project Goal
The goal of this project is to find the best ML and NN model to predict the number of Rings (directly related to age). This is a Supervised Learning ML challenge where Rings can be treated as a discrete (Classification) or continuous (Regression) problem.

* Machine Learning Models Used
  * Linear Regression Models
    * scikit-learn LinearRegression
    * scikit-learn Ridge
    * scikit-learn LASSO
    * scikit-learn ElasticNet    
  * Classification Models
    * scikit-learn LogisticRegression
    * scikit-learn KNN
    * scikit-learn RandomForest
    * scikit-learn SVM
  * H2O AutoML
  
* Neural Network Models Used
  * Regression Models
    * Simple
    * Deep
  * Classification Models
    * Simple
    * Deep

![image](https://user-images.githubusercontent.com/61704055/94387647-c4f27900-0118-11eb-8195-13629721084f.png)
![image](https://user-images.githubusercontent.com/61704055/94387734-05ea8d80-0119-11eb-8235-b0bc13463b5a.png)
![image](https://user-images.githubusercontent.com/61704055/94387739-0c790500-0119-11eb-882e-0d110c229499.png)
![image](https://user-images.githubusercontent.com/61704055/94387912-8e692e00-0119-11eb-8a03-871b0aaa5159.png)
![image](https://user-images.githubusercontent.com/61704055/94387914-91641e80-0119-11eb-942b-2e4a15a05819.png)
![image](https://user-images.githubusercontent.com/61704055/94387919-93c67880-0119-11eb-83d4-3b664cd9d02c.png)
![image](https://user-images.githubusercontent.com/61704055/94387922-96c16900-0119-11eb-857d-09dce1192ef0.png)
![image](https://user-images.githubusercontent.com/61704055/94387926-9a54f000-0119-11eb-92bd-6df67e66b0a0.png)
![image](https://user-images.githubusercontent.com/61704055/94387935-a50f8500-0119-11eb-9178-55eb16d6f8ef.png)
![image](https://user-images.githubusercontent.com/61704055/94387941-a8a30c00-0119-11eb-8734-46e6752ce4d3.png)
![image](https://user-images.githubusercontent.com/61704055/94387965-b8225500-0119-11eb-90f6-114ec527da94.png)
![image](https://user-images.githubusercontent.com/61704055/94387977-bbb5dc00-0119-11eb-932a-dc552cd9e40f.png)
![image](https://user-images.githubusercontent.com/61704055/94387987-bf496300-0119-11eb-8139-54a57356f9d8.png)
![image](https://user-images.githubusercontent.com/61704055/94387992-c2dcea00-0119-11eb-951f-28ea30c4bda0.png)
![image](https://user-images.githubusercontent.com/61704055/94387999-c6707100-0119-11eb-9443-ccef1dc1ab7e.png)
![image](https://user-images.githubusercontent.com/61704055/94388006-ca03f800-0119-11eb-952b-f88d5ff608e8.png)
![image](https://user-images.githubusercontent.com/61704055/94388011-cd977f00-0119-11eb-9b73-5aff3aba73e7.png)
![image](https://user-images.githubusercontent.com/61704055/94388016-d0926f80-0119-11eb-8063-0a30d00d6d2c.png)
![image](https://user-images.githubusercontent.com/61704055/94388019-d425f680-0119-11eb-9eac-975666bd15ed.png)
![image](https://user-images.githubusercontent.com/61704055/94388025-d8521400-0119-11eb-8802-89d8224722bc.png)
![image](https://user-images.githubusercontent.com/61704055/94388027-dbe59b00-0119-11eb-8119-6a734ecabe68.png)
![image](https://user-images.githubusercontent.com/61704055/94388033-e011b880-0119-11eb-9143-d56f679905af.png)
![image](https://user-images.githubusercontent.com/61704055/94388039-e3a53f80-0119-11eb-82b8-941e39175442.png)
![image](https://user-images.githubusercontent.com/61704055/94388042-e738c680-0119-11eb-8b11-b1f46fc79259.png)
![image](https://user-images.githubusercontent.com/61704055/94388046-eacc4d80-0119-11eb-807e-20f18f074d5b.png)
![image](https://user-images.githubusercontent.com/61704055/94388054-eef86b00-0119-11eb-9191-0a908c296a39.png)
![image](https://user-images.githubusercontent.com/61704055/94388060-f28bf200-0119-11eb-8791-10bfc40e6455.png)
![image](https://user-images.githubusercontent.com/61704055/94388065-f586e280-0119-11eb-9e9a-4c3e7f64dd3c.png)


















