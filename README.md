/******************************************************************************

 * Copyright (C) 2017 by Alex Fosdick - University of Colorado

 * @author Adrian Fornaso
 * @date 03/13/2020

 *****************************************************************************/
 
/**
 *
 *********************************** @brief ***********************************
 
 * In this programming assignment we create a simple application that performs
 * statistical analytics on a dataset. This assignment helps you get
 * re-oriented with c-programming syntax and host machine compilation. We begin
 * by setting up a version control repository on the local machine. And then
 * develop and test the code there. When complete, you will upload a zip of
 * your repository to Coursera. Please read through all instructions before
 * starting.
 
 * After completing this assignment, you will be able to:

 * Write a simple programming assignment that prints statistics to the command
 * line using a variety of c-programming operators and features.
 * Perform Compilation with GCC and execute output files from the command line.
 * Use git Version control to create a repository to version control code.
 


 ****************** Implementation File Guidelines - stats.c ******************

 * You are to write a couple of functions that can analyze an array of unsigned
 * char data items and report analytics on the maximum, minimum, mean, and
 * median of the data set. In addition, you will need to reorder this data set
 * from large to small. All statistics should be rounded down to the nearest
 * integer. After analysis and sorting is done, you will need to print that
 * data to the screen in nicely formatted presentation. You will need to submit
 * a version controlled repository of these 3 files.

 * stats.c - Implementation file for your C-programming code
 * stats.h - Header file for your C-programming code
 * README.md - Includes information on the author and the project
 

 * Eight functions in the stats.c implementation file are defined:

 * 1.   main() - The main entry point for your program
 
 * 2.   print_statistics() - A function that prints the statistics of an array
 *      including minimum, maximum, mean, and median.

 * 3.   print_array() - Given an array of data and a length, prints the array
 *      to the screen

 * 4.   find_median() - Given an array of data and a length, returns the median
 *      value

 * 5.   find_mean() - Given an array of data and a length, returns the mean

 * 6.   find_maximum() - Given an array of data and a length, returns the
 *      maximum

 * 7.   find_minimum() - Given an array of data and a length, returns the
        minimum
        
 * 8.   sort_array() - Given an array of data and a length, sorts the array
        from largest to smallest. (The zeroth Element should be the largest
        value, and the last element (n-1) should be the smallest value. )

 * To print data to the screen, we use the printf function provided by the
 * standard IO library (stdio.h). Each printed value is nicely formatted with
 * an indicator of the variable or index for each statistic value printed.

 * Most of the functions in the stats.c file require 2 input parameters and one
 * return value:

 * Input: An unsigned char pointer to an n-element data array
 * Input: An unsigned integer as the size of the array
 * Output: An unsigned char result from the function
 
 

 ********************** Header File Guidelines - stats.h **********************

 * The stats.h header includes declarations and documentation for the functions
 * from the stats.c file. Function declarations for all required functions are
 * added except main. With each declaration comments are provided with a
 * description of the function, the inputs, and return value.
 
 */
