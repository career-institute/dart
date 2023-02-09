# Assignments
## Assignment 1
You need to make a recursive login system that will ask for a username and password. If the username and password are correct, the program will print "Welcome to the system" and will end. If the username and password are incorrect, the program will ask for the username and password again. The program will ask for the username and password 3 times. If the username and password are incorrect 3 times, the program will print "Access denied" and will end. The username and password are "admin" and "1234" respectively.
### Sample Output
```bash
Enter username: admin
Enter password: 4321
Access denied

Enter username: admin
Enter password: 1234
Welcome to the system
```
## Assignment 2
You need to make a program that will ask for a number and will print the factorial of that number. For example, if the number is 5, the program will print 120. If the number is 0, the program will print 1. If the number is negative, the program will print "Invalid number". The program will ask for a number 3 times. If the number is invalid 3 times, the program will print "Invalid number" and will end. <br> _Note: Use recursion and functions._
### Factorial 
Factorial is a mathematical operation that multiplies a number by all the numbers below it. For example, 5 factorial is 5 * 4 * 3 * 2 * 1 = 120. 0 factorial is 1. Negative numbers don't have a factorial.
### Sample Output
```bash
Enter a number: 5
120
```

## Assignment 3
Concepts: Use Exception Handling and Asynchronous Programming for Input Validation of an email address.
You need to make a program that will ask for an email address and will print "Valid email address" if the email address is valid and will print "Invalid email address" if the email address is invalid. The program will ask for an email address 3 times. If the email address is invalid 3 times, the program will print "Invalid email address" and will end. <br> _Note: Use exception handling and asynchronous programming._

### Valid Email Address
Regex for valid email address: 
```
^[a-zA-Z0-9.!#$%&'*+/=?^_`{|}~-]+@[a-zA-Z0-9-]+(?:\.[a-zA-Z0-9-]+)*$
```
### Sample Output
```bash
Enter email address: abccompany.com
Invalid email address

Enter email address: abc@company.com
Valid email address
```


