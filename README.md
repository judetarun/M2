# EX-06 - Looping
## AIM:
Write a C program to print even numbers ranging from M to N (including M and N values).

## ALGORITHM:
1.	Declare two integer variables to store the values of M and N.
2.	Use the printf function to prompt the user to enter the values of M and N.
3.	Use the scanf function to read the values of M and N from the user.
4.	Use a loop (for or while) to iterate from M to N.
5.	Inside the loop, check if the current number is even.
6.	If the current number is even, print it.
7.	Continue the loop until you have iterated through all numbers from M to N.

## PROGRAM:
```
#include<stdio.h>
int main()
{
    int m,n;
    scanf("%d %d",&m,&n);
    for(int i=m;i<=n;i++){
        if(i%11==0){
            printf("%d ",i);
        }
    }
    return 0;
}
```
## OUTPUT:

![image](https://github.com/user-attachments/assets/216505fb-cece-4d47-937c-dbd66a3550c7)









## RESULT:
Thus the program to print even numbers ranging from M to N (including M and N values) has been executed successfully
 
 


# EX-07-Nested-loop

## AIM:

Write a C program to print the given triangular pattern using loop.

## ALGORITHM:

1.	Declare a variable to store the number of rows in the triangle.
2.	Use the printf function to prompt the user to enter the number of rows.
3.	Use a loop (for or while) to iterate through each row.
4.	Inside the loop, use another loop to print the desired number of asterisks for each row.
5.	Continue the loop until you have printed the entire triangular pattern.

## PROGRAM:
```
#include<stdio.h>
int main()
{
    int i,j,r;
    scanf("%d",&r);
    for(i=r;i>=1;i--){
        for(j=1;j<=i;j++){
            printf("#");
        }
        printf("\n");
    }}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/3b5b68c2-8503-42e8-a2e8-1d3d12417c41)





## RESULT:

Thus the program to print the given triangular pattern using loop has been executed successfully
 
 


# EX-08-Functions

## AIM:

Write a C program to perform mutiplication and division of two numbers using functions (with argument and without return type).

## ALGORITHM:

1.	Declare two functions, one for multiplication and one for division. Both functions should take two integer arguments.
2.	Inside the multiplication & division function, multiply & dicide the two numbers and print the result.
3.	In the main function, declare two integer variables and read their values from the user.
4.	Call the multiplication and division functions, passing the two numbers as arguments.
5.	end 

## PROGRAM:
```
#include<stdio.h>
void multy(int a,int b)
{
    int result=a*b;
    printf("Multiplication: %d\n",result);
}
void divi(int a,int b)
{
    float re=a/b;
    printf("Division: %f",re);
}
int main()
{
int a;
scanf("%d",&a);
int b;
scanf("%d",&b);
multy(a,b);
divi(a,b);
return 0;
}


```

## OUTPUT:
![image](https://github.com/user-attachments/assets/dd46c6d3-e617-4fd3-a7b8-e1e1e7313637)






## RESULT:

Thus the program to perform mutiplication and division of two numbers using functions has been executed successfully
 
 


# EX-09-Use While Loop

## AIM:

Write a c program to find the sum of even digits using while loop 

## ALGORITHM:

1.	Declare variables to store the input number and the sum of even digits.
2.	Initialize the sum of even digits to 0.
3.	Use a while loop to iterate through each digit of the input number.
4.	Inside the loop, extract the rightmost digit of the number (using the modulo operator % and division by 10).
5.	If the digit is even, add it to the sum of even digits.
6.	Print the sum of even digits.

## PROGRAM:
```
#include<stdio.h>
int main()
{
    int n,sum=0,i;
    scanf("%d",&n);
    i=1;
    while(i<=n){
        if(i%2==0)
            sum+=i;
        i++;
        
    }
    printf("%d",sum);
    printf("\n");
    return 0;
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/51ed0b96-63c0-4e2e-85f4-1f80f95075ec)




## RESULT:

Thus the program to find the sum of even digits using while loop has been executed successfully.




# EX – 10 - switch case
## AIM:
To write a C program to check a number is positive or negative using switch case.

## ALGORITHM:
1. Start.
2. Input an integer num.
3. Check if the number is positive:
4. If num > 0, then the number is positive. Print "num is positive.".
5. Else if the number is negative
6. If num < 0, then the number is negative. Print "num is negative.".
7. Else the number must be zero
8. If num == 0, then the number is zero. Print "num is zero.".
9. End.



## PROGRAM:
```
#include <stdio.h>

int main()
{
    int num;
    scanf("%d", &num);

    switch (num > 0){
        case 1:
        printf("%d is positive.", num);
        break;
        case 0:
        printf("%d is negative.", num);
        break;
}
    return 0;
    
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/f0a4a2b9-24e1-4b71-b7e5-3d8e9f876fff)

## RESULT:
The program correctly to check a number is positive or negative using switch case displays the result.
 
