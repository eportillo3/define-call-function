<h1>Define and call a function</h1>

<h2>Introduction</h2>

As a security analyst, when you're writing out Python code to automate a certain task, you'll often find yourself needing to reuse the same block of code more than once. This is why functions are important. You can call that function whenever you need the computer to execute those steps. Python not only has built-in functions that have already been defined, but also provides the tools for users to define their own functions. Security analysts often define and call functions in Python to automate series of tasks.

In this lab, you'll practice defining and calling functions in Python.

<h2>Scenario</h2>

Writing functions in Python is a useful skill in your work as a security analyst. In this lab, you'll define and a call a function that displays an alert about a potential security issue. Also, you'll work with a list of employee usernames, creating a function that converts the list into one string.

<h3>Task 1</h3>

The following code cell contains a user-defined function named alert().

For this task, analyze the function definition, and make note of your observations.

You won't need to run the cell in order to answer the question that follows. But if you do run the cell, note that it will not produce an output because the function is just being defined here.

<img src="https://i.imgur.com/M7XwxQ2.png" height="80%" width="80%"/>

<h3>Task 2</h3>

For this task, call the alert() function that was defined earlier and analyze the output.

Be sure to replace the ### YOUR CODE HERE ### with your own code before running the following cell.

<img src="https://i.imgur.com/GWzm4DQ.png" height="80%" width="80%"/>

<h3>Task 3</h3>

Functions can include other components that you've already worked with. The following code cell contains a variation of the alert() function that now uses a for loop to display the alert message multiple times.

For this task, call the new alert() function and observe the output.

Be sure to replace the ### YOUR CODE HERE ### with your own code before running the following cell.

<img src="https://i.imgur.com/vEqoIli.png" height="80%" width="80%"/>

<h3>Task 4</h3>

In the next part of your work, you're going to work with a list of approved usernames, representing users who can enter a system. You'll be developing a function that helps you convert the list of approved usernames into one big string. Structuring this data differently enables you to work with it in different ways. For example, structuring the usernames as a list allows you to easily add or remove a username from it. In contrast, structuring it as a string allows you to easily place its contents into a text file.

For this task, start defining a function named list_to_string(). Write the function header.

Be sure to replace the ### YOUR CODE HERE ### with your own code. Note that running this cell will produce an error since this cell will just contain the function header; you'll write the function body and complete the function definition in a later task.

<img src="https://i.imgur.com/kVT3r51.png" height="80%" width="80%"/>

<h3>Task 5</h3>

Now you'll begin to develop the body of the list_to_string() function.

In the following code cell, you're provided a list of approved usernames, stored in a variable named username_list. Your task is to complete the body of the list_to_string() function. Recall that the body of a function must be indented. To complete the function body, write a loop that iterates through the elements of the username_list and displays each element. Then, call the function and run the cell to observe what happens.

Be sure to replace each ### YOUR CODE HERE ### with your own code before running the following cell.

<img src="https://i.imgur.com/v4va4nL.png" height="80%" width="80%"/>

<h3>Task 6</h3>

String concatenation is a powerful concept in coding. It allows you to combine multiple strings together to form one large string, using the addition operator (+). Sometimes analysts need to merge individual pieces of data into a single string value. In this task, you'll use string concatenation to modify how the list_to_string() function is defined.

In the following code cell, you're provided a variable named sum_variable that initially contains an empty string. Your task is to use string concatenation to combine the usernames from the username_list and store the result in sum_variable.

In each iteration of the for loop, add the current element of username_list to sum_variable. At the end of the function definition, write a print() statement to display the value of sum_variable at that stage of the process. Then, run the cell to call the list_to_string() function and examine its output.

Be sure to replace each ### YOUR CODE HERE ### with your own code before running the following cell.

<img src="https://i.imgur.com/AFJVM43.png" height="80%" width="80%"/>

<h3>Task 7</h3>

In this final task, you'll modify the code you wrote previously to improve the readability of the output.

This time, in the definition of the list_to_string() function, add a comma and a space (", ") after each username. This will prevent all the usernames from running into each other in the output. Adding a comma helps clearly separate one username from the next in the output. Adding a space following the comma as an additional separator between one username and the next makes it easier to read the output. Then, call the function and run the cell to observe the output.

Be sure to replace each ### YOUR CODE HERE ### with your own code before running the following cell.

<img src="https://i.imgur.com/EuF7usY.png" height="80%" width="80%"/>
