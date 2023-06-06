# CSE 15L Lab 5 Report 
# Haotong Wu 
# June 5, 2023
## Part 1 -  Debugging Scenario (Scenario 2）
Run the bash script which clones a repo into student submissions directory and checks if the file is correct & runs JUnit tests on the program.
Error - There is an exception in which the terminal cannot locate the class path. (i.e. Class not found)

<img width="511" alt="捕获" src="https://github.com/timhaotongwu/cse15l-lab-reports/assets/122568570/3e925ded-7dc0-42e1-aa07-df246428835d">

After this repo cloned already from the previous lab. What we did to reproduce the error was change the CPATH variable and take out the lib directory in the beginning and ran the script with the same github repo link.

What makes this frustrating from the screenshot is that it excludes the first two lines, which is where the error is. Looking at the code on github, we see “CPATH='.:hamcrest-core-1.3.jar:lib/junit-4.13.2.jar' “. Here, we see that lib is missing, which is why the class cannot be found. So the change should just be adding lib: “CPATH='".:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar"'

People definitely have made some sort of this mistake before, I do too. I think especially since the JUnit path is long and complicated (i.e. semicolons instead of colons for windows vs linux), it is easy to dismiss the details of the JUnit path, which means it is easier to make mistakes there.


## Part 2 - Reflection 

