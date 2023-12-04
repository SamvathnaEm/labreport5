# Lab Report 5

## Part 1 - Debugging Scenario

1. The original post on EdStem:

Student(Sam): 

Hello guys, 
I have some issues with my code in a ```ListExamples.java``` class specifically in the merge method since it doesn't pass all of the tests on the test file ```TestListExamples.java```. I think the bugs might be in the if-conditional statement that I set in line #15, but I am not too sure if it will be the only thing that causes the errors. Other than this, I don't know how to set up other conditional statements to satisfy the requirements. Here are the screenshots showing a symptom on the terminal, along with the code in ```ListExamples.java``` and ```TestListExamples.java```.

![Image](1new.png)
![Image](2new.png)


TA's response:
Hi Sam,
You're right. I also think your code in line #15 might be the leading cause of the tests' failure. I suggest you develop a new if-conditional statement in line #15 again and repurpose the behavior of the merge method. I think the behavior in your merge method seems to be different from the requirements. Hence, it will produce a different output. Instead of comparing the length of the string within each element from each list, I recommend comparing the string values to maintain alphabetical order. Let me know if you have any further questions.

3. Another screenshot/terminal output showing what information the student got from trying that, and a clear description of what the bug is

Student's response: Ohh! I think I got what the overall behavior of the merge method is supposed to be. It intends to merge two lists and return a new list that has all the strings in both lists in sorted order, specifically in alphabetical order. In order to address the issue from my code, I just modified the if-conditional statement in line #15. In terms of the comparison logic, the correct comparison should be 
```list1.get(index1).compareTo(list2.get(index2)) < 0 ```. This would ensure that the strings from each list are compared based on their lexicographical order and, therefore, return one merged list containing all of the elements from two lists in sorted order.

Here's the screenshot of running the ```bash test.sh``` after fixing the bugs: 
![Image]((3).png)

It passes all the tests!


4. At the end, all the information needed about the setup, including:
The file & directory structure needed:


The contents of each file before fixing the bug: 


The full command line (or lines) you ran to trigger the bug: 


A description of what to edit to fix the bug:



## Part 2 - Reflection
A couple of things from my lab experience in the second half of this quarter that I didn't know before is creating a grading script to auto-grade student programming assignments. I have wondered how those things work behind the scenes since I took the introductory Java course. I am now able to write a grading script for programming assignments by myself and even know some cool useful commands like ```find``` , ```grep```, ```less``` that help facilitate the grading process.  
