# How to use the dplyr package in r programming by a practical example

## What is dplyr ?

dplyr is a powerful library for manipulating data frames in r programming providing a consistent set of verbs that help you solve the most common 
data manipulation problems.

### Functionalities

    mutate() adds new variables that are functions of existing variables
    select() picks variables based on their names.
    filter() picks cases based on their values.
    summarise() reduces multiple values down to a single summary.
    arrange() changes the ordering of the rows.

### Introduction

When you’re working with data, you need to figure out what you want to do, describe those tasks in the form of a computer program, and run the program.

The dplyr package makes these steps quick and easy:

    By limiting your options, it helps you think through your data manipulation challenges.
    It provides simple “verbs,” functions that correspond to the most common data manipulation tasks, to help you translate your thoughts into code.
    It uses efficient backends so you spend less time waiting on the computer.
  ### Data

To explore the functionalities of dplyr, we will use the data come from data.gov. This dataset provides information regarding the total approved actual 
expenses incurred by Montgomery County government employees traveling non-locally (over 75 miles from the County’s Executive Office Building at 101 Monroe St.
Rockville, MD) for official business, beginning on or after August 12, 2015. The dataset includes the name of traveling employee; the employee’s home department; 
travel start and end dates; destination; purpose of travel; and actual total expenses funded by the County. Update Frequency: Monthly


  
