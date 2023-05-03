Download Link: https://assignmentchef.com/product/solved-cs1xc3-assignment-4-dynamic-memory-allocation
<br>
<ul>

 <li>Write a C program that uses dynamic memory allocation.</li>

</ul>

<strong> </strong>Requirements

Create a program that will dynamically allocate space for an array of doubles according to the user’s requested size, fill that array with values from user input, and then sort the array with insertion sort.

The program should ask the user to enter the number of elements.  You can assume that the user will enter a positive integer value and do not need to perform input validation.

The program should dynamically allocate space for an array of doubles that can store this many elements.  The program should then ask the user to input a double value for each element one at a time, “Enter element 0”, “Enter element 1”, etc.  Each double value that the user inputs should be stored in the array in the order they are entered.  Again you can assume the user will enter valid double values and you do not need to perform input validation.

After the user has finished entering the required number of values, print out the unsorted array (with 2 decimal digits of precision for each element).

The array should then be sorted from the highest to lowest using the <strong>insertion sort</strong> algorithm.

Implement the insertion sort algorithm in C.  You can find a pseudocode version of it here: <a href="https://en.wikipedia.org/wiki/Insertion_sort">https://en.wikipedia.org/wiki/Insertion_sort</a><a href="https://en.wikipedia.org/wiki/Insertion_sort">.</a>  Translating it to C can be done in about 10 lines of code.

After the array has been sorted, print out the sorted array (again with 2 decimal digits of precision).  Remember to free the dynamically allocated memory.




Your program should function identically or near identically to this sample program.














