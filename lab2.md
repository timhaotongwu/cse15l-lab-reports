# CSE 15L Lab 2 Report 
# Haotong Wu 
# May 1, 2023

## Part 1 - Write a web server called `StringServer`that supports the path and behavior described below. 
It should keep track of a single string that gets added to by incoming requests. 


## Part 2 - Choose one of the bugs from lab 3 and Briefly describe why the fix addresses the issue.

<img width="450" alt="Screen Shot 2023-05-10 at 10 05 27 AM" src="https://github.com/timhaotongwu/cse15l-lab-reports/assets/122568570/eae6c640-0bf1-4ab2-b51b-dbbce8f9f9ea">


The ReverseInPlace bug: the original array was updated while using its own contents to update it to be in reverse order, so the list would only be in reverse order up to half the list.

Reversed bug: all contents of the new list was 0, which meant that the list updating was not working as intended. The bug is that the new array is not being updated correctly and it is not returned.

Fixes: in Reversed, swap newArray and arr (just the words, not the indexing) and then change the return to be newArray. In reverseInPlace, you would loop through only half the array length and then also use a temporary variable to store the value of the index to be updated, and then also update the array from the back (i.e. length - 1 - i).


## Part 3 - In a couple of sentences, describe something you learned from lab in week 2 or 3 that you didn’t know before.

