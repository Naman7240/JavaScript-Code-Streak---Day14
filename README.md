JavaScript Code of Streak - Day14

Q)Write a JavaScript program to get the first n Fibonacci numbers.

Explanation:

Recursive approach have been used to write the program.
The factorial of a non-negative number,n, is computed as the product of all integers between 1 and n (both inclusive).

 factorial(n)=n * (n-1) * ... * 1
 factorial(n)=n∗(n−1)∗...∗1
It can also be thought of as:
 factorial(n)=n * factorial(n-1)
 factorial(n)=n∗factorial(n−1)
The factorial of n can be found by finding the factorial of a number one less than n, and then multiplying this answer with n.
So the factorial of n-1 can be thought of as a subproblem that needs to be computed first.

![image](https://user-images.githubusercontent.com/117966470/213623403-d298018f-686a-4931-a941-d2b895549ad9.png)

