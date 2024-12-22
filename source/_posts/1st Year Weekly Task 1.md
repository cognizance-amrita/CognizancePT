---
title: 1st Year Weekly Task 1
---

_Welcome to the Cognizance Weekly Task, Solve the given set of problems to earn XP Points_

_**<span style="color: #90EE90;">Note:</span> You are not compelled to do all the questions from all the domains, But the more you do the more you learn and gain XP Points.**_

<hr>

**<span style="color: #90EE90; font-size: 1.5rem;">Open Source</span>**
 
**<span style="color: #ADD8E6; font-size: 1rem;">Authors - Rohith Prasanna and Jahnavi</span>**

**<span style="color: #ADD8E6; font-size: 1rem;">Todo-list</span>**

<span style="color: #ADD8E6;">_Objective:_</span>
- To design and develop a **Web Application for Task Management** that enhances productivity and helps users to stay organized.
- Your goal is to create a responsive and interactive system that incorporates essential functionalities for task management while offering a seamless user experience.

<span style="color: #ADD8E6;">_Instructions:_</span>

1. **Understand the Requirements**: Analyze the core functionalities described below and ensure your web application fulfills these requirements.  
2. **Plan Your Implementation**: Strategize the structure of your web application, including UI/UX design, backend logic, and database management.  
3. **Develop the Application**: Use suitable web technologies (e.g., HTML, CSS, JavaScript, React, Node.js, or Django) to build the application.  
4. **Test Your Application**: Ensure the application is bug-free, user-friendly, and meets the expected outcomes across different devices.  

<span style="color: #ADD8E6;">_Core Functionalities:_</span>

 1. #### Task Creation 
Users should be able to:  
- Add tasks with descriptive titles using a user-friendly input form.  
- Include  details such as due dates and time.
- Your can add additional features too.

2. #### Task Viewing
- Display tasks in a structured list or grid format.  
- Implement a feature to view the remaining task [apart from completed task] .  

3. #### Task Management 
- Mark tasks as completed.  
- Edit or delete tasks directly from the interface.  

4. #### Responsive 
- Ensure that the web application is responsive and works seamlessly.


<span style="color: #ADD8E6;">_Example Workflow :_</span>

#### Todo list

- **Add a Task** : A user will have to fill the inputs like topic, due date and due time , then clicks the add task button.

- **View Tasks** : The user sees all tasks displayed in a visually appealing layout, sorted by priority, with "Complete project report" at the top.  

- **Mark as Completed** : Once the task is done, the user clicks a checkbox to mark it as completed , remaining tasks will be decremented by 1.

- **Edit or Delete** : The user can easily modify the due date or remove unnecessary tasks via edit or a delete button.  


<span style="color: #ADD8E6;">_Evaluation Criteria :_</span>

- Functionality : Does the web application implement all the core features effectively?  

- Usability : Is the application intuitive and easy to navigate?  

- Design & Responsiveness : Does the application provide an aesthetically pleasing and responsive interface?  

- Inovation  : Innovation (additional features or UI) plays a major role in this task.

<span style="color: #ADD8E6;">_Submission Guidelines:_</span>
- **Hosting in github**: Your website should be hosted in github page .
- **Person's name**: Person's name should be mentioned somewhere in the website .  
- **Implementation**: Your github repository link and website page link should be submitted in the submission form .  
- **Pull Request**: Create a pull request from your `submission` branch to the `main` branch of the original repository.  
- **Final Check**: Ensure that your github repository is made public .

<span style="color: #ADD8E6;">_References:_
- [<span style="color: #55AAFF;">Todo-list</span>](https://www.youtube.com/watch?v=3OqWCGVaOkA&ab_channel=HowtoBecomeaDeveloper)
- [<span style="color: #55AAFF;">HTML </span>](https://www.youtube.com/watch?v=FQdaUv95mR8&ab_channel=KevinStratvert)
- [<span style="color: #55AAFF;">CSS </span>](https://www.youtube.com/watch?v=wRNinF7YQqQ&ab_channel=BroCode)
- [<span style="color: #55AAFF;">JS</span>](https://www.youtube.com/watch?v=W6NZfCO5SIk&ab_channel=ProgrammingwithMosh)
- [<span style="color: #55AAFF;">Github Hosting </span>](https://www.youtube.com/watch?v=BT4WzyT2g8k&ab_channel=AKRITIGOSWAMI )

  
<hr>
<hr>


**<span style="color: #90EE90; font-size: 1.5rem;">AI</span>**

**<span style="color: #ADD8E6; font-size: 1rem;">Authors - Shalini D and Jeba Rachel</span>**

---

**<span style="color: #FF6363; font-size: 1rem;">Task 1: Model Selection for Regression with Scikit-learn</span>**

**<span style="color: #ADD8E6;">Objective:</span>**  
Build a regression model to predict diabetes progression using Scikit-learn. This task will help you understand the fundamentals of selecting and evaluating regression models.  

**<span style="color: #ADD8E6;">Dataset:</span>**  
Diabetes Dataset (available in Scikit-learn).  

---

**<span style="color: #ADD8E6;">Steps</span>**

1. **Load the Dataset**  
   - Use Scikit-learn to load the Diabetes dataset.  
   - Convert it into a Pandas DataFrame for preprocessing.  

   **Code:**  
   ```python
   from sklearn.datasets import load_diabetes
   import pandas as pd
   data = load_diabetes()
   df = pd.DataFrame(data.data, columns=data.feature_names)
   df['progression'] = data.target
   df.to_csv("diabetes.csv", index=False)
   ```

2. **Preprocess the Data**  
   - Load the CSV file using Pandas.  
   - Check for missing values and handle them if present.  
   - Standardize numerical features using `StandardScaler`.  

3. **Model Selection**  
   - Compare multiple regression models, such as Linear Regression, Ridge Regression, and Random Forest Regressor.  
   - Use cross-validation to evaluate model performance using Mean Squared Error (MSE).  

4. **Train and Test the Best Model**  
   - Split the data into training and testing sets (80-20 split).  
   - Train the selected model on the training set.  
   - Evaluate its performance on the test set.  
---

**<span style="color: #ADD8E6;">Deliverables</span>**  

- A Google Colab Notebook containing:  
  - Code for data preprocessing, model comparison, and evaluation.  
  - Comments explaining each step.  
  - A summary of the best model and its MSE on the test set.  

---

**<span style="color: #FF6363; font-size: 1rem;">Task 2: Model Selection for Classification with Scikit-learn</span>**

**<span style="color: #ADD8E6;">Objective:</span>**  
Build a classification model to predict iris species using Scikit-learn. This task focuses on understanding the process of selecting the best classification model.

**<span style="color: #ADD8E6;">Dataset:</span>**  
Iris Dataset (available in Scikit-learn).

---

**<span style="color: #ADD8E6;">Steps</span>**

1. **Load the Dataset**  
   - Use Scikit-learn to load the Iris dataset.  
   - Convert it into a Pandas DataFrame for preprocessing.  

   **Code:**  
   ```python
   from sklearn.datasets import load_iris
   import pandas as pd
   data = load_iris()
   df = pd.DataFrame(data.data, columns=data.feature_names)
   df['species'] = data.target
   df.to_csv("iris.csv", index=False)
   ```

2. **Preprocess the Data**  
   - Load the CSV file in Pandas.  
   - Handle missing values if present.  
   - Standardize numerical features using `StandardScaler`.  
   - Encode the target variable using label encoding.  

3. **Model Selection**  
   - Compare multiple classification models, such as Logistic Regression, Decision Trees, and Support Vector Machines (SVM).  
   - Use cross-validation to evaluate model performance using accuracy and F1-score.  

4. **Train and Test the Best Model**  
   - Split the data into training and testing sets (80-20 split).  
   - Train the selected model on the training set.  
   - Evaluate its performance on the test set.

---

**<span style="color: #ADD8E6;">Deliverables</span>**  

- A Google Colab Notebook containing:  
  - Code for data preprocessing, model comparison, and evaluation.  
  - Comments explaining each step.  
  - A summary of the best model and its accuracy and F1-score on the test set.  

---

**<span style="color: #ADD8E6;">References</span>**

**General References:**  
1. **Regression:**  
   - [Scikit-learn Regression Guide](https://scikit-learn.org/stable/supervised_learning.html#supervised-learning)  
   - [StandardScaler Documentation](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.StandardScaler.html)  


2. **Classification:**  
   - [Scikit-learn Classification Guide](https://scikit-learn.org/stable/supervised_learning.html#classification)  
   - [Cross-validation](https://scikit-learn.org/stable/modules/cross_validation.html)  

**Specific Techniques:**  
- **Data Splitting:** [Train-Test Split](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.train_test_split.html)  
- **Handling Missing Values:** [Pandas Documentation](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.fillna.html)  
- **Model Selection:** [GridSearchCV](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GridSearchCV.html)  


**Note:** Complete each task in Google Colab and upload your notebooks to your GitHub profile.

<hr>
<hr>

**<span style="color: #90EE90; font-size: 1.5rem;">Cyber Security</span>**
 
**<span style="color: #ADD8E6; font-size: 1rem;">Authors - Sreeram Rohith and Keerthi Rohan</span>**

**<span style="color: #FF6363; font-size: 1rem;">Question 1</span>**

**<span style="color: #ADD8E6; font-size: 1rem;">Image Steganography</span>** 


<span style="color: #ADD8E6;">_Objective:_</span>
Create a Python GUI using Tkinter to perform image steganography with the following objectives:

1. Allow the user to upload an image.
2. Use a steganography algorithm to embed text into the image.
3. Provide functionality in the GUI to decode the hidden text from the image.

Submission Guidelines:

1. Include your name and the task name in the file.
2. Provide an explanation of how the algorithm works (Many Algorithms are there . Mention the name of Algorithm)
3. Include input and output images.
4. Mention your Learning Outcomes(what modules and libraries you have learnt. List out those)
5. Create a GitHub repository and upload both the PDF file and the code.
6. Submit the Github repository link in the forms
   
(PDF Should contain Submission guidelines 1,2,3,4)

<span style="color: #ADD8E6;">_References:_
- [<span style="color: #55AAFF;">Reference - 1: </span>](https://www.geeksforgeeks.org/image-steganography-in-cryptography/)
- [<span style="color: #55AAFF;">Reference - 2: </span>](https://www.geeksforgeeks.org/python-gui-tkinter/)
  
<hr>
<hr>

**<span style="color: #90EE90; font-size: 1.5rem;">Competitive Programming</span>**

**<span style="color: #ADD8E6; font-size: 1rem;">Authors - Adithiyan PV and Shyam</span>**

**<span style="color: #FF6363; font-size: 1rem;">Objective:</span>**  
This task focuses on solving 5 problems related to arrays in a HackerRank contest. It’s designed to help you build your problem-solving and coding skills while exploring competitive programming.  

<span style="color: #ADD8E6;">_Contest Link:_</span>  
[<span style="color: #55AAFF;">Weekly Task 1 for First Year</span>](https://www.hackerrank.com/weekly-task-1-year)  

---

<span style="color: #ADD8E6;">_Reference Links:_</span>  

1. [<span style="color: #55AAFF;">Brush up on the Basics</span>](https://youtu.be/n60Dn0UsbEk?si=tKA9hbZGBvYRImYF)  
2. [<span style="color: #55AAFF;">Advanced Interview Prep Playlist</span>](https://youtube.com/playlist?list=PLgUwDviBIf0rENwdL0nEH0uGom9no0nyB&si=WCOhz25J0Ce4iHci)
   
---

### **<span style="color: #FF6363; font-size: 1.2rem;">Hints for the Problems</span>**

**<span style="color: #ADD8E6;">Problem 1: Climbing the Leaderboard</span>**  
- Use reverse traversal or binary search for efficient score comparison.  
- Maintain a dynamic rank list to adjust rankings as you process player scores.  

**<span style="color: #ADD8E6;">Problem 2: Forming a Magic Square</span>**  
- Precompute all 8 unique 3x3 magic squares.  
- Calculate the minimal cost of converting the input matrix into one of these magic squares.  

**<span style="color: #ADD8E6;">Problem 3: Picking Numbers</span>**  
- Use a frequency array or dictionary to count occurrences of numbers.  
- Check adjacent pairs in the frequency array to find the largest subset where the difference between numbers is at most 1.  

### **<span style="color: #FF6363; font-size: 1rem;">Important Note:</span>**  
Kindly refrain from using AI tools to generate your solutions. This exercise is tailored to boost your logical reasoning and enhance your coding expertise.  

Reach out to your mentors for any doubts—they’re here to support you!

<hr>
<hr>

**<span style="color: #90EE90; font-size: 1.5rem;">Submission</span>**
**<span style="color: #FF6363; font-size: 1rem;">Deadline - 1st January 2025, 23:59 </span>**

**NOTE: Create a GitHub Repository named "Cognizance_1st_Year_T1". For each domain create a separate directory namely "OS", "AI", "CYS", and "CP".  For each domain question, create a sub-directory, "Q1", and "Q2". Finally, update the relevant files in these directories and fill out the submission form by providing the links to these repos**

```bash
└── Cognizance_1st_Year_T1
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

[<span style="color: #55AAFF;">Submission Forms</span>](https://forms.gle/9F2VhDUcUU6q6o8BA)
