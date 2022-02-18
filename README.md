
# Machine Learning Classification on Fruit and MNIST dataset
I am Rachel Conforti this project is for ITCS5156 - Applied Machine Learning taken in Spring 2022 at University of North Carolina at Charlotte. This is a 8-week accelerated course.

# Dataset:
The MNIST dataset can be found here http://yann.lecun.com/exdb/mnist/
![image](https://user-images.githubusercontent.com/50918318/151715870-646c140d-e907-48eb-9e58-72465c6e8499.png)

The way I used the dataset in my project was by using the skleran dataset import to make this simple.
  from sklearn import datasets
  digits is the MNIST dataset. 
  
The Fruit datset can be found here https://www.kaggle.com/moltean/fruits
![image](https://user-images.githubusercontent.com/50918318/154775067-081ad4fa-9815-4076-84fd-5fa1c72d9259.png)

This was a bit more invloved trying to use this dataset. Download the dataset from Kaggle it is to large to import here.  

# Goal and Weekly Updates:
The paper I am attempting to duplicate is Handwritten Digits Identification using Mnist Database Via Machine Learning Models. They used multiple types of models such as Support Vector Machine, Multilayer Perceptron, Decision Tree, Naïve Bayes, K-Nearest Neighbor, and Random Forest. I will attempt to use these models on the MNIST dataset as well and see if I can get a similar accuracy on them. 

###### Week 1:
I completed the Support Vector Machine, Multilayer Perceptron, Decision Tree, Naïve Bayes, K-Nearest Neighbor, and Random Forest. I completed the side by side bar chart of accuracy and I placed in confusion matrixs as well. The paper did not use confusion matrixs but I thought this would be a fun and interesting addition. This can all be seen in the project file.

###### Week 2:
Was informedthat my dataset was a benchmark dataset and should change. I will be testing out different image datasets to replicate the paper. I have a few that I messing around with and seeing how I like them.

###### Week 3:
I spent this week trying to figure out how to import the dataset and make it useable. It was a adventure trying to set this up but it got done.

##### Week 4:
I finished the code to do both greyscale photos and binary scale photos. I got it printing out both models for each set. I am going a little adrift from my paper due to the change in dataset so I will be comparing how this data is working compared to the MNIST dataset. 

# How to run the project
Open up andaconda, and run the project line by line waiting for each cell to populate. I seperated each into their own juypter notebook to make it a bit more readable

# Citation:
Gope, Birjit, et al. "Handwritten Digits Identification using Mnist Database Via	Machine	Learning Models." IOP Conference Series.Materials Science and	Engineering, vol. 1022, no. 1, 2021. ProQuest, https://www.proquest.com/scholarly-journals/handwritten-digitsidentification-using-mnist/docview/2601103602/se-2,	doi:http://dx.doi.org/10.1088/1757-899X/1022/1/012108
