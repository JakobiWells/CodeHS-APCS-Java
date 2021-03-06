# Number Histogram App
Tags: `arrays` `for loops` `randomizer`

**Description:** In this program, an array is created with 25 elements. For each element in the array we are assigning a random number between 0 - 9 (results will be printed into the console). Afterwards, count how many times each number is inside the data array.



## Objective:
A histogram represents the distribution of numerical data - essentially a count of the number of occurences of a particular piece of data. Write a program that creates a basic "number histogram".

First, create an array with 25 elements, like this (use this variable name):

`init[] data = new int[25];`

Using a for loop, change the value *at each index* in `data` to a randomly generated integer from 0 - 9. The `data` array should contain different values everytime your program runs.

Declare and initialize a second array that will represent the histogram:
`int[] histogram = new int[10];`

`histogram` will be used to store the number of times each number (0-9) occurs in `data`. Your solution should NOT have variables for each value (e.g. `int = num0 = 0`, `num1 = 0`, `num2 = 0`, etc.), or use ten if statements inside the loop - you need to think with arrays!

# Setup:
![Instructions](https://github.com/Tanner1638/CodeHS-APCS-Java/blob/master/Sandbox%20Projects/ignore/Capture.PNG)
1. Create a new file in the sandbox and name it `Randomizer.java` then copy and paste the code as found in this repo called `Randomizer.java`.
2. Afterwards, copy and paste `MyProgram.java` into your `MyProgram.java`.
