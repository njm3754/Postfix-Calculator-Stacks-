# Postfix-Calculator-Stacks-
I am creating a program which reads multi digit integers from a file and displays the result after postfix operation

Right now my main code just reads single digit integers and to find a way with which it will read multidigit integers from a file and perform 
operations on it.

For example my file looks like this 
5 6 + 0 +
7 2 - 0 *

250 900 + 800*


The program displays the output as
Expression: 5 6 + 0 +
Value: 11

Expression: 7 2 - 0 *
Value: 0

Expression: 250 900 + 800 * 
Value: ERROR

I need to find a way to make it read multi digit integers. NOTE the program reads one characracter at a time from the file with help of get(Ch) function. 




