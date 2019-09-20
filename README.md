# CSCI390_as02
Assignment 2 on CSCI390 Artificial Intelligence course

# Assignment 02
In this assignment, there are three python files implement the MINIMAX algorithm: 

- **as2_tree.py:** this class transforms a list of data into a tree. Do not change this file.
- **as2_mnx.py:** you will ***work*** on this file only.
- **as2_test.py:** you can use this file to test your implementation. In this file, we included a list of data that provides the terminal value for the tree. During the lecture (19th Sep 2019), we will explain how to init the tree by using the list. Anyone that misses the lecture, please consult with your friend. We will not disclose it again.

 **Tasks:** two tasks need to be fulfilled:

1. There are four (4) logical errors, which are intentionally put inside the file: **as2_mnx.py**. You have to find **ALL** the errors and fix them. Otherwise, your code will not work correctly. For example, the result of the *best terminal value* in the root should be '3' instead of '6'. (2 points)
1. Implement the additional code (also in the file: **as2_mnx.py**) to return the *traversed_solution* in the form of an array. For example: ['A', 'X', 'Y'], with A is the root node, X is the child of A, Y is the leaf node containing the best terminal value (which is 3). Apparently, Y the child of X. (3 points)

Remember to put the *best terminal value* and the *traversed_solution* into the object ***res***, which is an instance of the class *Result*. We have already included an example of how to use this object in the file: **as2_mnx.py** (from line 33 to line 39). 

 **Policy:**

- Program crash: **0 points**. We also made an auto-grader. If our grader cannot run your implementation, you will get **0 points**. Therefore, please keep the **name of functions**, the **input parameters**, and the **output**.
- There is a runnable example of the output in **as2_test.py**. You might test the case by yourself.
- Plagiarism: **0 points**. Before we do the grading, we will check the code similarity to make sure that no one copies and pastes the code from others.
- Grading environment: **Python 3.7.4 on Windows 10**. You can use Anaconda with Jupyter to debug. However, if your code cannot run on the terminal in the grading environment, you will get **0 points**.
- Deadline: 7th Oct 2019 (after the fall break), 23:59.
