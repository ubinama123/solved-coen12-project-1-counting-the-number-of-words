Download Link: https://assignmentchef.com/product/solved-coen12-project-1-counting-the-number-of-words
<br>
In this project, you will implement an application to read words from a text file. The filename will be supplied on the command line. Your program should display the total number of words in the file. (Consider a word to be a sequence of non-white-space characters.) Here is an example of how your program will be run:

$ ./a.out /scratch/coen12/Macbeth.txt

18464 total words

<h1>1        Implementation</h1>

This project is designed to refresh your programming skills, in addition to motivating later projects. If you need any help with the assignment, seek out help from the instructor or teaching assistant (but not from other students). There is no reason (besides lack of effort) why you should not receive a perfect score!

You can assume that there is a maximum word length. However, this value should be properly declared as a symbolic constant and documented:

# define MAX_WORD_LENGTH 30

Your program should work correctly on all of the example files under /scratch/coen12. To make grading easier, please match the example output shown above.