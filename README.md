Download Link: https://assignmentchef.com/product/solved-cse1321-lab12-single-dimensional-arrays
<br>
<strong><u>Exercise #1:</u></strong> Design and implement a program (name it AssignGrades) that stores and processes numeric scores for a class. The program prompts the users to enter the class size (number of students) to create a single-dimensional array of that size to store the scores. The program prompts the user to enter a valid integer score (between 0 and 100) for each student. The program validates entered scores, rejects invalid scores, and stores only valid scores in the array.

The program defines method printGrades() that takes a signal-dimensional array of integer scores as a parameter and processes the scores to print letter grades based on the following scale:




Grade is A if score &gt;= 90 and score &lt;= 100

Grade is B if score &gt;= 80 and score &lt;= 89

Grade is C if score &gt;= 70 and score &lt;= 79

Grade is D if score &gt;= 60 and score &lt;= 69

Grade is F if score &lt; 60




Document your code and organized your output following these sample runs.




<u>Sample run 1:</u>




Class size:     5

Entered grades: 90, 67, 78, 89, 60

Student 0 score is 90 and grade is A

Student 1 score is 67 and grade is D

Student 2 score is 78 and grade is C

Student 3 score is 89 and grade is B

Student 4 score is 60 and grade is D




<u>Sample run 2:</u>




Class size:     3

Entered grades: 77, 50, 81

Student 0 score is 77 and grade is C

Student 1 score is 50 and grade is F

Student 2 score is 81 and grade is B







<strong><u>Exercise #2:</u></strong> Design and implement a program (name it CompareArrays) that compares the content of 2 single-dimensional arrays of the same size. The program prompts the users to enter the array size. Then prompts the user to initialize each array with integer values. The program defines method Compare() that takes two signal-dimensional arrays of type integer. The method compares the content of the arrays and returns true (Boolean type) if the arrays store same values in the same order. Otherwise, it returns false. The program main method calls method Compare()and prints the result from the method as shown below. Document your code and organized your output following these sample runs.




<u>Sample run 1:</u>

Array size:     4

First array:    23, -45, 78, 10

Second array:   23, -45, 78, 10Judgment:       The arrays are identical




<u>Sample run 2:</u>




Array size:     5

First array:    78, 128, 300, 12, 300

Second array:   78, 128, 12, 300, 300Judgment:       The arrays are not identical




<u>Sample run 3:</u>




Array size:     1

First array:    0

Second array:   0Judgment:       The arrays are identical







<strong><u>Exercise #3:</u></strong> Design and implement a program (name it ArrayMethods), that defines 4 methods as follows:




<strong>int arrayMax(int[] arr)</strong> returns the maximum value in the an array

<strong>int arrayMin(int[] arr)</strong> returns the minimum value in an array

<strong>void arraySquared(int[] arr)</strong> changes every value in the array to its square (value²)

<strong>void arrayReverse(int[] arr)</strong> reverses the array (for example: array storing 7   8   9  becomes 9   8   7 )




The program main method creates a single-dimensional array of length 5 elements and initialize it with random integers between 1 and 100. The program displays the original array, then calls each of the above methods and displays their results as shown below. Document your code and organized your output following these sample runs.




<u>Sample run 1:</u>




Original array: 3, 5, 2, 6, 1

Max value:      6

Min value:      1

Squared array:  9, 25, 4, 36, 1

Reversed array: 1, 36, 4, 25, 9




<u>Sample run 2:</u>




Original array: 3, 2, 3, 7, 2

Max value:      7

Min value:      2

Squared array:  9, 4, 9, 49, 4

Reversed array: 4, 49, 9, 4, 9




<u>Sample run 3:</u>




Original array: 2, 2, 2, 2, 2

Max value:      2

Min value:      2

Squared array:  4, 4, 4, 4, 4

Reversed array: 4, 4, 4, 4, 4


