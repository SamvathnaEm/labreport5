# Lab Report 5

## Part 1 - Debugging Scenario

1. The original post on EdStem:

Student(Sam): 

Hello guys, 
I have some issues with my code in a ```ListExamples.java``` class specifically in the merge method since it doesn't pass all of the tests on the test file ```TestListExamples.java```. I think the bugs might be in the if-conditional statement that I set in line #15, but I am not too sure if it will be the only thing that causes the errors. Other than this, I don't know how to set up other conditional statements to satisfy the requirements. Here are the screenshots showing a symptom on the terminal, along with the code in ```ListExamples.java``` and ```TestListExamples.java```.

![Image]((1).png)
![Image]((2).png)


TA's response:
Hi Sam,
You're right. I also think your code in line #15 might be the leading cause of the tests' failure. I suggest you develop a new if-conditional statement in line #15 again and repurpose the behavior of the merge method. I think the behavior in your merge method seems to be different from the requirements. Hence, it will produce a different output. Instead of comparing the length of the string within each element from each list, I recommend comparing the string values to maintain alphabetical order. Let me know if you have any further questions.

3. Another screenshot/terminal output showing what information the student got from trying that, and a clear description of what the bug is


4. At the end, all the information needed about the setup, including:
The file & directory structure needed:

The contents of each file before fixing the bug: 

The full command line (or lines) you ran to trigger the bug: 

A description of what to edit to fix the bug:



## Part 2 - Reflection
A couple of things from my lab experience in the second half of this quarter that I didn't know before is creating a grading script to auto-grade student programming assignments. I have wondered how those things work behind the scenes since I took the introductory Java course. I am now able to write a grading script for programming assignments by myself and even know some cool useful commands like ```find``` , ```grep```, ```less``` that help facilitate the grading process.  
