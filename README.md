# EX-2-A-LOOPS
## AIM :
Write a C program to print 1 to n numbers in Reverse Order. 
## ALGORITHAM :
1.Start

2.Declare a variable to store the limit (n) and a loop counter variable (e.g., i).

3.Prompt the user to enter the value of n.

4.Read the value of n from the user.

5.Initialize the loop counter i to n.

6.Use a loop to iterate from i down to 1 (inclusive):
a. Print the current value of i.
b. Decrement i by 1.

7.End.
## PROGRAM :
```
#include<stdio.h>
int main(){
int n;
scanf("%d",&n);
int i =n;
while(i<=n){
if(i==0)
Break; {
printf("%d ",i);
i--;
}
}
return 0;
}
```
## OUTPUT :
![image](https://github.com/Niroshassithanathan/EX-2-A-LOOPS/assets/121418437/bb90313b-bb71-4307-a0ed-c3da8cb1b154)

## RESULT :
Thus , The C program has been executed.
