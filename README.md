1. """Given an integer, , perform the following conditional actions:

If  is odd, print Weird
If  is even and in the inclusive range of  to , print Not Weird
If  is even and in the inclusive range of  to , print Weird
If  is even and greater than , print Not Weird"""

n = input()
if n % 2 != 0:
       print("Weird")
       
else:
        print ("Not Weird")

2.Task
The provided code stub reads two integers from STDIN,  and . Add code to print three lines where:

The first line contains the sum of the two numbers.
The second line contains the difference of the two numbers (first - second).
The third line contains the product of the two numbers.

a = input()
b = input()
print (a + b)
print (a - b)
print (a * b)

3.Task 
# Python: Division

# Task 
# Read two integers and print two lines. The first line should contain integer division, a // b. The second line should contain float
# division, a / b.

# You don't need to perform any rounding or formatting operations.

# Input Format 
# The first line contains the first integer, a. The second line contains the second integer, b.

# Output Format 
# Print the two lines as described above.

# Enter your code here. Read input from STDIN. Print output to STDOUT
a = input()
b = input()
print (int(a//b))
print float(a) / b

4.Task
