# codechef-beginners-small-factorials
You are asked to calculate factorials of some small positive integers.

Input
An integer t, 1<=t<=100, denoting the number of testcases, followed by t lines, each containing a single integer n, 1<=n<=100.

Output
For each integer n given at input, display a line with the value of n!

Example
Sample input:
4
1
2
5
3
Sample output:

1
2
120
6

solve:


# cook your dish here
t=int(input())
f=1
if(t>=1 and t<=100):
    for i in range(t):
        n=int(input())
        for j in range(1,n+1):
            f=f*j
        print(f)        
        f=1
