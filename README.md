# CS-201-01-13F-Programming-In-C-Program-5-solution

Download Here: [CS 201-01-13F Programming In C++ Program 5 solution](https://jarviscodinghub.com/assignment/cs-201-01-13f-programming-in-c-program-5-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

Create a folder called “PG5” in the top level of your CS201-01-13F folder. Place all files pertaining to this assignment into that folder. Place a (possibly empty) file called “DONE” into this folder when you are ready to have your programs graded. The only files you need to turn in are the .cpp files. The .h files are provided and must be used as provided without alteration. Your main method is not to use ComparableString and ComparableInt except to make new objects. You are to use Comparable to access the methods within the objects.
You are to design a collection of classes with inheritance that can store an array of either integer or string. (You may assume that the array will never store a mixture of integer and string; it will either be one or the other.)
The class should have a method that extracts the largest value from the array, either integer or string, and another extracts the smallest. Note that there should be only one “largest” and one “smallest” method, and they should just work no matter whether there are integers or strings in the array. When it compares integers, it should compare integers normally, but when it compares strings it should compare them case insensitively.
Your main should first read in the size of an array of integers, and then read in those integers one at a time. It should then print the largest and smallest integers in that array using the objects and method described above.
It should then read in the size of an array of string, and then read in the strings one at a time. When it prints the largest and smallest strings, it should print them in the case they were entered, even though the program ignores case when it compares them.
Example:
How many integers? 3 Enter an integer: 4 Enter an integer: 1 Enter an integer: 2
The largest integer is 4 and the smallest is 1.
How many strings? 3 Enter a string: cAt Enter a string: BAT
Enter a string: ape
The largest string is cAt and the smallest is ape.
