EX: 7.1 RECURSION

Aim: To Write a Python Program to find the sum of all digits in a number using recursion
Algorithm:
STEP 1: Start.

STEP 2: Define a function.

STEP 3: Create a base case for termination of the function. STEP 4: Create a recursive case to calculate the result.

STEP 5: Print the result. STEP 6: Stop.

Program:

reg no:212223070012
name:Lithick Kumar M N
def sum_digit(n):
       if n<=0:
            return 0
       else:
            return n%10+sum_digit(n//10)
n = int(input())
sum = sum_digit(n)
print(sum)
Output:
<img width="821" height="52" alt="439812625-f8a856c5-040c-441e-b28e-9f3882bd6410" src="https://github.com/user-attachments/assets/9f682ac3-0312-4dbd-bd51-be008447879b" />


Result:
Thus, the given program is implemented and executed successfully .
