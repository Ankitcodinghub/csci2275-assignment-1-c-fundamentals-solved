# csci2275-assignment-1-c-fundamentals-solved
**TO GET THIS SOLUTION VISIT:** [CSCI2275 Assignment 1-C++ Fundamentals Solved](https://www.ankitcodinghub.com/product/csci2275-csci-2270-ae-data-structures-assignment-1-c-fundamentals-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;119700&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI2275  Assignment 1-C++ Fundamentals Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Objectives

1. Read-in command line arguments

2. Read a file

3. Loop through an array

4. Split a string

5. Create an array of struct types

6. Read and Write to a file

Instructions

Write code to complete Parts 1 and 2. Implement the solution for each part as a separate program. To receive credit for your code, you will need to pass the necessary test cases. Use the following steps to test your code as you work on the assignment:

1. Open up your Linux terminal, navigate to the build directory of this assignment (e.g. cd build).

2. Run the cmake .. command.

3. Run the make command.

4. If there are no compilation errors, three executables will be generated within the build directory: run_app_1, run_app_2, and run_tests.

5. If you would like to run your program including your app implementation in the main function, execute run_app_1 from the terminal by typing ./run_app_1 ../numbers.txt. Similarly, you can execute run_app_2 with the correct command line arguments.

6. To run the grading tests, execute run_tests from the terminal by typing ./run_tests.

For Part 2 of the assignment, substitute ./run_app_2 for ./run_app_1 and follow the same steps.

Part 1 – Reading From a File Into a Sorted Array

Overview: Write a program that reads up to 100 numbers from a file. As you read the numbers, insert them into an array in descending order.

For Part 1, your task is to implement the functions in code_1undamentals_1.cpp with the associated function prototypes located in code_1undamentals_1.hpp. The main function is defined in app_1main_1.cpp. You are encouraged to use main_1.cpp to test your functions as you implement them.

Part 1-A

Implement a function called addToArrayDesc that does the following:

Takes in three arguments:

sortedArray[ ] : sorted array that should be able to hold at most 100 floats numElements : the number of elements inserted so far.

newValue : the incoming float value to be inserted into the sortedArray.

Inserts newValue into sortedArray such that the array is ordered in descending order.

Returns an integer containing the count of the elements inserted so far (i.e. the current size of the array).

The function header will appear as follows: int addToArrayDesc(float sortedArray[], int numElements, float newValue);

Note: You are not permitted to use any library functions (i.e. sort from the &lt;algorithm&gt; library)

Part 1-B

In this section you will write a complete program in app_1main_1.cpp: * Read a test file: Your program should take a single command line argument containing the name of the test data file. * Assume that the file is stored in the same directory as your program. * Open the file: * If there is an error in opening the file, use the following error message and terminate execution, std::cout &lt;&lt; â€œFailed to open the file.â€ &lt;&lt; std::endl; * Your program can expect the file to contain up to 100 numbers on separate lines. For testing you can use the provided file named â€œnumbers.txtâ€, or create your own if you prefer. * Create an array of floats to store at most 100 floats. * Use the getline function to read the numbers one at a time. * Store these numbers in a sorted array by passing them to the addToArrayDesc function (use your implementation from Part 1-A). * Each time a new number is read, print out the entire array after insertion, as shown in the example below.

| Input FileContents: arr.txt | Desired Output: | |:————————— |—————–| | 1 | 1 | | 6 | 6,1 | | 2 | 6,2,1 | | 12 | 12,6,2,1 | | 5 |

12,6,5,2,1 |

Part 2 – Working With an Array-of-Structs

Overview: In this part of the assignment you will also work with reading in data from an external file. Likewise, your program will write data out to a file, and store data in the program’s memory within an array-of-structs data structure.

Implement the functions in code_2undamentals_2.cpp with the associated function prototypes located in code_2undamentals_2.hpp. The main function is defined in app_2main_2.cpp. You are encouraged to use main_2.cpp to test your functions as you implement them. Specifications

Your program will accomplish the following:

1. Read a csv file with 5 columns and up to 10 lines containing information on student grades.

2. Store the information in an array-of-structs.

3. Record the results name, score, and grade out to output.csv.

4. Write a subset of the array to standard output and external file.

Create an array that holds the studentData struct objects. Use the following struct declaration:

struct studentData { string studentName; int homework; int recitation; int quiz; int exam; double average; };

Part 2-A

Write a function named addStudentData: * The addStudentData function has the following declaration: void addStudentData(studentData students[], string studentName, int homework, int recitation, int quiz, int exam, int length); * students[] is an

array-of-structs of studentData type * length is the number of items currently stored in the array * Within the function, instantiate a local studentData struct and store the studentName, homework, recitation, quiz, and exam values. * Assume equal weights amongst everything that needs to be graded. Take the average of the homework, recitation, quiz, and exam for each respective student and store it in the struct. * student.average = (homework + recitation + quiz + exam) / 4; * Add the struct to the students array.

Part 2-B

Write a function named calcLetterGrade: * The calcLetterGrade function has the following declaration: char calcLetterGrade(double avg);

Write IF-ELSE conditions to assign letter grades based on the following

|&gt;=90:| A | |—–|—-| |80-89.9:|B| |70-79.9:|C| |60-69.9:|D| |&lt;60: |F|

Return the letter grade.

Part 2-C

Write a complete program which includes the following: 1. The struct and functions listed above. 2. A main() function defined as below: 1.

Expect four command line arguments 1. the name of the input â€œ.csvâ€ file 2. the name of the output â€œ.csvâ€ file 3. a low bound letter grade 4. an upper bound letter grade 2. Expect the input and output files to be stored in the same directory as your executable. Or else give proper path for files in command line arguments. 3. Read from the input file, students.csv: * Each line can be read and decomposed using any of the following: * getline function with the optional delimiter character. * stringstream object * Following the decomposition, convert each entry into its appropriate data type. Keep in mind that you must use the exact data types that are specified in the struct. (HINT: If needed, use stoi, stof functions to convert from string to numberical types) * Call addStudentData function to update the students array. 4. Writing out to external files in C++ can be done very similarly as reading in. Instead of using an object of the ifstream class, as is done with input streams, use an object of the ofstream class. csv stands for comma separated values. Write to an output â€œ.csvâ€ file: * Write the &lt;student_name&gt;,

&lt;student_average&gt;,&lt;letter_grade&gt; (as shown in the sample output) of the students whose &lt;letter_grade&gt; is &gt;= lower_bound and

&lt;letter_grade&gt; &lt;= upper_bound to the output .csv file. Here, lower_bound and upper_bound represent the letter grades passed as command-line arguments to the program. * Do not sort the data while writing to the output file. The relative order will be the same as the input file. Only those students with overall letter grade within the bounds should be written to the output file. 5. Make sure your program closes the output file when it is finished writing.

Sample Input and Output:

Assuming that the input file, students.csv has the following content: Tim Thomas,90,92,95,100 Bob Brown,80,90,88,81 Jenny Jackson,69,79,90,73 Samantha Smith,65,57,72,59 Ralph Rogers,55,59,62,48 Running your program using the command:

./run_app_2.out students.csv output.csv C A should produce the following file, output.csv: Tim Thomas,94.25,A Bob Brown,84.75,B Jenny Jackson,77.75,C
