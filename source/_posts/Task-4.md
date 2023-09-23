---
title: Task 4 ( 22nd SEP 2023 )
date: 2023-09-24 11:40:00
tags: Preliminary tasks
domain: AI
---

# Task-4

Following are the few subtasks that will help you run through the python essentials for getting started with AI and ML.

## Q1
File Handling is one of the basic important task when it comes to building machine learning models or neural networks. Building a good model always starts with finding datasets and processing it, for which, file handling acts as a stepping stone.

<br>

#### Write a python program that reads the contents from the given file 'onelinefile.txt'. The file contains a single line which is of the format (int)(string)(float)(string) repeatedly. For e.g. 
```
1Aaa3.5Maths2Bbb4.2Physics3Ccc7.62Chemistry
```
<br>

#### Your main task is to split the contents of the given file based on their format and write it into a .csv file say 'Filename2.csv'. For e.g. the above txt file should be converted into a csv file such that the contents look like this:

```csv
1,Aaa,3.5,Maths
2,Bbb,4.2,Physics
3,Ccc,7.62,Chemistry
```
<br>

### Contents of 'onelinefile.txt'
```
1Aaa3.5Maths2Bbb4.2Physics3Ccc7.62Chemistry4Ddd9.55Biology5Eee4.0Social6Fff7.6English7Ggg3.111Maths8Hhh9.99Physics9Iii1.23Civics
```

<br>

**Q2**

A Python library used for complex mathematical and statistical tasks and operations. It is one of the important libraries used in data preprocessing and ML/DL Algorithms. We can create from basic equations to some of the most complex Neural Network architectures using this. The first part of this task introduces you to the basics of Numpy.

You can use this command in your terminal to install Numpy

```
pip install numpy
```

<hr>

1. Create a single and multidimensional arrays using numpy and also create a array of numbers of a specified range.

2. Convert the above array to a 3 x 12 array.

3. Create a multidimentional square matrix and find the inverse of it. 

    ( _Use the the below formula to compute the inverse. <br>Use the inbuilt inverse command too to validate your results._ )

$$  inv(A) = {adj(A) \over{ |A| } }$$

4. Extract specific rows and columns using Slicing

5. Import data from files directly into ndarray using the loadtxt function.

<hr>

### References 📖
1. Numpy Docs : https://numpy.org/doc/stable/reference/index.html#numpy-reference
2. Numpy Tutorial : https://www.youtube.com/watch?v=QUT1VHiLmmI&pp=ygUFbnVtcHk%3D
3. Numpy Basics : https://medium.com/nerd-for-tech/a-complete-guide-on-numpy-for-data-science-c54f47dfef8d
4. Numpy Linear Algebra class : https://numpy.org/doc/stable/reference/routines.linalg.html



## Q3
#### Read the file 'about.txt' and find the words with atleast 6 letters and the most frequently used word.

<br>

Contents of the file 'about.txt':
```
Python has tools for almost every aspect of scientific computing. The Bank of America uses Python to crunch its financial data and Facebook looks upon the Python library Pandas for its data analysis. While there are many libraries available to perform data analysis in Python, here are a few: NumPy, SciPy, Pandas and Matplotlib. 
```

<br>

## Q4
#### Given food name, price, rating(out of 5) and their datatypes, create a structured array using NumPy and sort the array on rating

> [Dataset link](https://github.com/cognizance-amrita/AI-Tasks/blob/main/Task-1/Q4-Dataset.csv)

<br>

## Q5
#### Let x be the size of houses in sq feet. x can take values between 700 to 2400 and is a multiple of 10. The price of the house (y) is found by the equation y = 10\*x^2 + 2\*x.  
#### Pass the values into a .csv file and plot a graph of the prices against the size of houses. Provide appropriate labels for the axes.


<br><br>

## __Submission Link__(https://docs.google.com/forms/d/e/1FAIpQLSddEo2ZwppjMhXTnnXWKFvckpvluAyxH-j2MvCgkVLAUTWmlA/viewform?usp=sf_link)

