---
title: 1st Year Preliminary Task
---

_Welcome to the Cognizance Preliminary Task, Here you are asked to solve a few basic problems from each domain to make you understand each domain_

_**<span style="color: #90EE90;">Note:</span> You are not compelled to do all the questions from all the domains, But the more you do the more you learn and gain XP Points.**_

<hr>

**<span style="color: #90EE90; font-size: 1.5rem;">Open Source</span>**
**<span style="color: #ADD8E6; font-size: 1rem;">Authors - Jahnavi and Nehal Khan</span>**

**<span style="color: #FF6363; font-size: 1rem;">Question 1</span>**

**<span style="color: #ADD8E6; font-size: 1rem;">Figma</span>**

**Figma is a web-based tool for graphics editing and user interface design. It allows you to create a wide range of design projects, including website wireframes, mobile app interfaces, design prototypes, social media posts, and more**

<span style="color: #ADD8E6;">_Objective:_</span>
- Design an attractive landing page for a Website/App of your own.
  (Example - Front Web Page of Amazon.com)
  
- The Landing page can be of your own choice, It doesn't need to be a real live Website/App.
  
- Make the design look as elaborate and enhanced as possible
  
- Make sure the design is eye-catching

*Note: Based on you're performance, you may also get an opportunity to make Posters/Web designs for the club in the future.*

<span style="color: #ADD8E6;">_References:_
- [<span style="color: #55AAFF;">Figma Basics</span>](https://www.youtube.com/watch?v=FTFaQWZBqQ8&pp=ygUOZmlnbWEgdHV0b3JpYWw%3D)

<span style="color: #ADD8E6;">_Submission Guidelines:_</span>
- Submit the Figma link in the submission forms.
  
<hr>

**<span style="color: #FF6363; font-size: 1rem;">Question 2</span>**

**<span style="color: #ADD8E6; font-size: 1rem;">RDBMS</span>**

**MySQL is a popular open-source relational database management system (RDBMS) that uses Structured Query Language (SQL) for managing and organizing data. Known for its speed, reliability, and ease of use, MySQL is widely used in web applications, data warehousing, and logging applications making it a top choice for developers and organizations to handle large volumes of data efficiently**

<span style="color: #ADD8E6;">_Preparatory Step:_</span>
- Download MySql from [<span style="color: #55AAFF;">mysql.org</span>](https://dev.mysql.com/downloads/mysql/)
- Use the *MySQL Command Line Client* to do the tasks and not *MySQL WorkBench*

<span style="color: #ADD8E6;">_Objective:_</span>

You are tasked with creating a small database system to manage student memberships in the Cognizance club at Amrita University. The system should track which students are part of this club and what technical language they are familiar with.
  
- <span style="color: #FF6363;">Question 2.1 : </span>Create a database called "Clubs" in MySQL and then create a table called "Cognizance" with columns "Name" (student's name), and "Known_language" (Python, C, C++, Java, etc.).
  
- <span style="color: #FF6363;">Question 2.2 : </span>Populate the _Cognizance_ table with at least 5 students ensuring a mix of different _Known_language_.
  
- <span style="color: #FF6363;">Question 2.3 : </span>Now display the names of all students who have "Python" as their _known_language_.
  
- <span style="color: #FF6363;">Question 2.4 : </span>Update the _known_language_ of the first student that you have inserted into any other language and display the updation by showing the whole table again.


<span style="color: #ADD8E6;">_References:_</span>
- [<span style="color: #55AAFF;">MySQL Queries</span>](https://www.javatpoint.com/mysql-queries)
- [<span style="color: #55AAFF;">MySQL Instalation</span>](https://www.youtube.com/watch?v=u96rVINbAUI)

<span style="color: #ADD8E6;">_Submission Guidelines:_</span>
- Take screenshots for each input and output and make a document.
- Submit the document in the GitHub directory.

<hr>
<hr>


**<span style="color: #90EE90; font-size: 1.5rem;">AI</span>**
**<span style="color: #ADD8E6; font-size: 1rem;">Authors - R. Pranav and Jagaadhep U K</span>**

**<span style="color: #ADD8E6; font-size: 1rem;">Google Colab</span>**

**Google Colab is a free online tool that lets you write and run Python code right in your web browser. It's like a notebook where you can type your code and see the results immediately. Colab is great for learning and working on data science projects because it supports popular Python libraries like Pandas and TensorFlow. You can also use it with others, making it easy to collaborate on projects. Plus, it provides access to powerful computers (GPUs and TPUs) for faster processing, which is really helpful for running complex tasks.**

**Note: Use Google Colab to complete the tasks provided. After completing the tasks, upload your Google Colab Notebook to your GitHub repository.**

<span style="color: #ADD8E6;">_References:_</span>
- [<span style="color: #55AAFF;">Google Colab tutorial</span>](https://www.youtube.com/watch?v=rsBiVxzmhG0)

<hr>

**<span style="color: #FF6363; font-size: 1rem;">Question 1</span>**

**<span style="color: #ADD8E6; font-size: 1rem;">Numpy</span>**

**NumPy is a popular Python library used for working with numbers and arrays. Think of it as a tool that helps you do math and handle large sets of numbers easily. It makes it simple to perform calculations on lists of numbers and matrices. NumPy is great for anyone who wants to do data analysis or scientific computing because it speeds up these tasks with its fast and powerful features.**

**<span style="color: #ADD8E6; font-size: 1rem;">DataSet</span>**

We use a dataset of details about 15 students each having attributes – Height, Weight, Age, Average Grade and Courses. We use the python code given below to create a NumPy array of our dataset.

**Python code to create NumPy array for the task:**

```lua

import numpy as np
# Creating a dataset with 15 students and 5 attributes
data = np.array([
    [170, 65, 19, 85, 5],
    [180, 75, 20, 90, 6],
    [160, 55, 18, 80, 4],
    [175, 70, 21, 88, 7],
    [155, 50, 19, 82, 5],
    [165, 62, 22, 89, 6],
    [178, 80, 23, 91, 7],
    [162, 58, 20, 78, 3],
    [172, 68, 19, 86, 5],
    [169, 66, 20, 84, 4],
    [171, 64, 22, 87, 6],
    [177, 72, 21, 90, 9],
    [174, 76, 24, 88, 8],
    [158, 52, 18, 75, 3],
    [164, 63, 19, 81, 4]
])

# Printing the dataset with student labels
print("Student\tHeight\tWeight\tAge\tAvg Grade\tCourses")
for index, student in enumerate(data):
    print(f"Student {index + 1}\t{student[0]}\t{student[1]}\t{student[2]}\t{student[3]}\t\t{student[4]}")
    
```

<span style="color: #ADD8E6;">_Objective:_</span>
- <span style="color: #FF6363;">Question 1.1 : </span>Find the Average Height of the Students
  
    Explanation: You need to use the mean() function from NumPy to compute the average value of the height column in the dataset.

- <span style="color: #FF6363;">Question 1.2 : </span>Find the Age of the Oldest Student

    Explanation: Use the max() function from NumPy to find the maximum value in the age column and determine the age of the oldest student.

- <span style="color: #FF6363;">Question 1.3 : </span>Find the Index of the Student Who Took the Most Courses

    Explanation: Use the argmax() function from NumPy to locate the index of the maximum value in the number of courses column.

- <span style="color: #FF6363;">Question 1.4 : </span>Find the Number of Students with an Average Grade Above 85

    Explanation: Use a NumPy condition to filter the dataset for students with an average grade above 85, and then use the sum() function to count them.

- <span style="color: #FF6363;">Question 1.5 : </span>Calculate the Ratio of a Student's Age to Their Average Grade for Each Student

    Explanation: Perform element-wise division of the age column by the average grade column to get the ratio for each student.
  
<span style="color: #ADD8E6;">_References:_</span>
- [<span style="color: #55AAFF;">W3Schools</span>](https://www.w3schools.com/python/numpy/default.asp)
- [<span style="color: #55AAFF;">Numpy Documentation</span>](https://numpy.org/doc/stable/reference/arrays.ndarray.html)
- [<span style="color: #55AAFF;">GeeksforGeeks</span>]( https://www.geeksforgeeks.org/numpy-tutorial/)
- [<span style="color: #55AAFF;">NumPy cheat sheet</span>](https://images.datacamp.com/image/upload/v1676302459/Marketing/Blog/Numpy_Cheat_Sheet.pdf)

<hr>

**<span style="color: #FF6363; font-size: 1rem;">Question 2</span>**

**<span style="color: #ADD8E6; font-size: 1rem;">Pandas</span>**

**Pandas is a powerful open-source data analysis and manipulation library for Python. It provides data structures like Data Frames and Series that are built on top of NumPy arrays and are designed to handle a wide range of data types and operations efficiently. Pandas is extensively used in data science and machine learning for tasks such as data cleaning, transformation, and analysis.**

**<span style="color: #ADD8E6; font-size: 1rem;">DataSet</span>**

*We will use a dataset with 15 students, each having 5 attributes. Let's first convert the list into a Pandas DataFrame.*
```lua
data = [
    [170, 65, 19, 85, 5],
    [180, 75, 20, 90, 6],
    [160, 55, 18, 80, 4],
    [175, 70, 21, 88, 7],
    [155, 50, 19, 82, 5],
    [165, 62, 22, 89, 6],
    [178, 80, 23, 91, 7],
    [162, 58, 20, 78, 3],
    [172, 68, 19, 86, 5],
    [169, 66, 20, 84, 4],
    [171, 64, 22, 87, 6],
    [177, 72, 21, 90, 9],
    [174, 76, 24, 88, 8],
    [158, 52, 18, 75, 3],
    [164, 63, 19, 81, 4]
]
# column names being ‘Height’, ‘Weight’, ‘Age’, ‘Avg_Grade’ and ‘Courses’ in that order.
```
<span style="color: #ADD8E6;">_Objective:_</span>
- <span style="color: #FF6363;">Question 2.1 : </span>Create a Pandas DataFrame

    Explanation: You need to understand how to convert a NumPy array into a DataFrame and assign column names.

- <span style="color: #FF6363;">Question 2.2 : </span>Describe the DataFrame

    Explanation: The describe() function provides various summary statistics (mean, standard deviation, min, max, and percentiles) for numeric columns in the DataFrame.

- <span style="color: #FF6363;">Question 2.3 : </span>Count the Number of Students in Each Age Group

    Explanation: Use the value_counts() function to count occurrences of unique values in a column.

- <span style="color: #FF6363;">Question 2.4 : </span>Filter the DataFrame

  Explanation: Filtering allows you to extract specific rows from the DataFrame based on certain conditions.

- <span style="color: #FF6363;">Question 2.5 : </span>Calculate the Average Grade for Each Age Group

  Explanation: The groupby() function in Pandas is used to group data based on one or more columns. After grouping, you can apply aggregation functions like mean() to these groups. In this task, you will group students by their age and then calculate the average grade for each age group.

<span style="color: #ADD8E6;">_References:_</span>
- [<span style="color: #55AAFF;">W3Schools</span>](https://www.w3schools.com/python/pandas/default.asp)
- [<span style="color: #55AAFF;">Pandas Documentation</span>](https://pandas.pydata.org/docs/reference/frame.html)
- [<span style="color: #55AAFF;">GeeksforGeeks</span>](https://www.geeksforgeeks.org/pandas-tutorial/)
- [<span style="color: #55AAFF;">Pandas cheat sheet </span>](https://pandas.pydata.org/Pandas_Cheat_Sheet.pdf)


<hr>
<hr>

**<span style="color: #90EE90; font-size: 1.5rem;">CYS</span>**  
**<span style="color: #ADD8E6; font-size: 1rem;">Authors - R. Subramanian and Rohan</span>**

**<span style="color: #ADD8E6; font-size: 1rem;">Recruitment Challenge</span>**  

**"Hello. We are looking for highly intelligent individuals. To find them, we have devised a test.
There are three images provided below, each containing a hidden message. Your task is to decode the hidden message within each image and follow the clues it reveals. We look forward to meeting the few that will make it all the way through.
Good luck.
3301"**

_<span style="color: #ADD8E6">Objective:</span>_

*Your task is to decode the hidden messages within the images provided. Use the resource [StegOnline Checklist](https://georgeom.net/StegOnline/checklist) to analyze the images and uncover the flags. Document your findings and upload the final output images.*

_<span style="color: #ADD8E6">Submission Guidelines:</span>_

- In the submission form, you have to type flag(finding) for each task (make sure ur flag is in this format *******{______} ).

_<span style="color: #ADD8E6">Task Descriptions:</span>_

- **Task 1**: "This garden contains more than it seems" - [Download](https://jupiter.challenges.picoctf.org/static/43c4743b3946f427e883f6b286f47467/garden.jpg)
  
- **Task 2**: "Files can always be changed in a secret way. Can you find the flag? (Hint: people use base64 to hide some info)" - [Download](https://mercury.picoctf.net/static/c28a959c5605d5f67480d5dd3a77f302/cat.jpg)
  
- **Task 3**: "There will always be more than what it seems to contain."- [Download](https://artifacts.picoctf.net/c/261/flag.png)

_<span style="color: #ADD8E6">Hints:</span>_

- Look for patterns, anomalies, or hidden elements in the images.
- Think beyond the obvious; not everything is as it seems.

_<span style="color: #ADD8E6">References:</span>_

- [<span style="color: #55AAFF;">Cicada 3301 Wiki</span>](https://en.wikipedia.org/wiki/Cicada_3301)
- [<span style="color: #55AAFF;">Reddit - r/Cicada3301</span>](https://www.reddit.com/r/cicada3301/)
- [<span style="color: #55AAFF;">Cybersecurity Capture the Flag (CTF) Guide</span>](https://ctf101.org/)
- [<span style="color: #55AAFF;">StegOnline Checklist</span>](https://georgeom.net/StegOnline/checklist)


<hr>
<hr>

**<span style="color: #90EE90; font-size: 1.5rem;">Competitive Programming</span>**
**<span style="color: #ADD8E6; font-size: 1rem;">Authors - Adithiyan PV and Kaushik Kumbhat</span>**

<span style="color: #ADD8E6;">_TASK:_</span>

CREATE AN ACCOUNT IN HACKERRANK PLATFORM AND JOIN IN THE HACKERRANK CHALLENGE VIA THE LINK GIVEN BELOW:

<span style="color: #ADD8E6;">_LINK:_</span> <https://www.hackerrank.com/cp-task-for-1st-year>

<span style="color: #ADD8E6;">_SCORING CRITERIA:_</span>

- Each challenge has a pre-determined score.

- A participant’s score depends on the number of test cases a participant’s code submission successfully passes.

- If a participant submits more than one solution per challenge, then the participant’s score will reflect the highest score achieved. In a game challenge, the participant's score will reflect the last code submission.

- Participants are ranked by score. If two or more participants achieve the same score, then the tie is broken by the total time taken to submit the last solution resulting in a higher score.

<span style="color: #ADD8E6;">_Study:_</span>

1. **Basic input and output:**

In programming, **input** and **output** are fundamental concepts that allow a program to interact with its environment, typically by receiving data from the user (input) and presenting results or information (output).

**A simple example of python code involving both user input and output:**

```lua
# Simple calculator

num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))

operation = input("Enter an operation (+, -, *, /): ")

if operation == "+":
    result = num1 + num2
elif operation == "-":
    result = num1 - num2
elif operation == "*":
    result = num1 * num2
elif operation == "/":
    result = num1 / num2
else:
    result = "Invalid operation"

print(f"The result is: {result}")
```

2. **Conditional statements:**

Conditional statements are a fundamental concept in programming that allows you to make decisions based on certain conditions. These statements enable your code to execute different blocks of code depending on whether specific conditions are met or not. In this blog post, we'll delve into the basics of conditional statements, starting with the ubiquitous if-else statement and gradually exploring more complex scenarios.

**A simple flowchart demonstrating the working of conditional statement is shown as below:**

![image](https://github.com/user-attachments/assets/322f144f-fc4e-4f11-9371-dff3858c70e2)

- 'if statement' is used to execute a block of code only if a certain condition is met. It allows us to conditionally execute code based on whether the specified condition is true.
- 'else statement', on the other hand, is an optional companion to the if statement. It specifies what code to execute if the condition in the if statement is not met (i.e. if it is false).

3. **Introduction to 'for' loop:**

A for loop is a control structure in programming that allows you to execute a specific block of code repeatedly. It's especially useful when you want to perform the same task multiple times without duplicating your code. Let's break down the essential components of a for loop:

**Initialization:** You declare and initialize a variable that serves as a counter. This step only happens once at the beginning.

**Condition:** You specify a condition that determines when the loop should stop executing.Increment/Decrement: You define how the counter variable changes after each iteration.

![image](https://github.com/user-attachments/assets/2cb7b64c-557b-4660-9f41-06b00cf31a7f)

![image](https://github.com/user-attachments/assets/514421c2-366e-4feb-833f-576d2408adef)

4. **Introduction to 'while' loop:**

A while loop follows a simple sequence of steps:**1\. Evaluation of Test Expression:** The loop begins by evaluating a test expression.Condition Check: If the test expression is true, the code inside the loop's body is executed.

**Re-evaluation:** After executing the code, the test expression is evaluated again.Continuation or Termination: This process continues until the test expression becomes false, at which point the while loop terminates.

![image](https://github.com/user-attachments/assets/cf65bd39-7114-433a-ab35-92d112e8e6a6)

While loops can be best illustrated with the practical example of finding the Factorial. Factorial of a number 'n' is the product of all positive integers from 1 to 'n'. To compute this using a while loop, we initialise a factorial variable to 1 and repeatedly multiply it by 'n' while decrementing 'n' until 'n' becomes 0. This ensures that we calculate the factorial correctly.

**5\. Introduction to functions:**

In programming, a **function** is a block of code designed to perform a specific task. Functions help organize code, make it reusable, and improve its readability. Instead of writing the same code multiple times, you can define a function once and call it whenever you need it.

**Why to use Functions?**

- **Reusability:** Write a function once, use it many times.
- **Organization:** Break down complex problems into smaller, manageable parts.
- **Modularity:** Functions allow you to organize code into separate sections.
- **Maintainability:** Easier to update code. Changes in a function are reflected wherever the function is used.

<hr>
<hr>

**<span style="color: #90EE90; font-size: 1.5rem;">Submission</span>**
**<span style="color: #FF6363; font-size: 1rem;">Deadline - 10th September 2024, 23:59 </span>**

**NOTE: Create a GitHub Repository named "Cognizance_1st_Year_PT". For each domain create a separate directory namely "OS", "AI", "CYS", and "CP".  For each domain question, create a sub-directory, "Q1", and "Q2". Finally, update the relevant files in these directories and fill out the submission form by providing the links to these repos**

```bash
└── Cognizance_1st_Year_PT
    ├── OS
    |   ├── Q1
    |   |   └── example.py
    |   └── Q2
    |       └── example.py
    ├── AI
    |   └── Q1
    |       └── example.py
    ├── CYS
    |   └── Q1
    |       └── example.py
    └── CP
        └── Q1
            └── example.py
```

[<span style="color: #55AAFF;">Submission Forms</span>](https://forms.gle/hKg2jYzTSaaCHV6c7)
