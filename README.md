1. Write a C compiler to check whether a given number is a valid floating point number or not. Write for all possible all test cases. Example:
input: 2.0
output: valid
input: 1.
output: invalid
2. Write a C program to check whether a given email is valid or not. Rules of email ID can be refer to
the link https://en.wikipedia.org/wiki/Email_address
3. Let us assume that A is a single dimensional array. You have given A array to construct a two-
dimensional array. Write a C program to convert explicitly from 2D array to 1D array. Example,
Map(A, i, j) gives you A[i][j]. You can use either row-major order or column-major order.
4. Write a C program to benchmark the performance of Selection Sort and Bubble Sort. Total input items may be randomly generated and already sorted. You have to tell your story using the bar chart
 as given below for an example.
10
 9
 8
 7
 6
 5
 4
 3
 2
 1
 0
Already sorted input Selection Sort Bubble Sort
                      10M
20M 30M 40M
Times in Seconds
10
 9
 8
 7
 6
 5
 4
 3
 2
 1
 0
Randomly generated input
Selection Sort
Bubble Sort
                      10M 20M
30M 40M
Note: To measure times, you need to include #include<time.h>
clock_t start, end;
long int t;
start=clock();
Selection sort algorithm end=clock();
t=end-start;
printf(“Total elapsed time : %f”, (double)t/(double)CLOCKS_PER_SEC);
Or you can directly measure $time ./a.out
real 0m5.959s user 0m3.900s sys 0m2.028s
You need to consider only the real part.
Times in Seconds




National Institute of Technology, Silchar,
Assignment 1,
Data Structures,
Course Code: CS 201

Manash Protim Borah
Scholar Id - 2012002
