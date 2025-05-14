
# EX-01-Datatypes-Operators
Name: Somesh Sanjay V
Register number: 24002358
## AIM:
Write a C program to read 3 characters one by one and print the characters in a reverse order.

## ALGORITHM:
1.	Declare three character variables to store the input characters.
2.	Use the scanf function to read the characters one by one from the user.
3.	Print the characters in reverse order using the printf function.
4.	End the program.

## PROGRAM:

```
#include <stdio.h>

int main() { char ch1, ch2, ch3;

scanf(" %c", &ch1);


scanf(" %c", &ch2);


scanf(" %c", &ch3);


printf("Characters in reverse order: %c %c %c\n", ch3, ch2, ch1);

return 0;
}
    
```

## OUTPUT:


![WhatsApp Image 2025-05-14 at 08 37 03_3af7bf8f](https://github.com/user-attachments/assets/bee8e03b-98b9-4c1f-8baa-ae9a13370822)















## RESULT:
Thus the program to read 3 characters one by one and print the characters in a reverse order has been executed successfully.


# EX-02- Conditional-Statements
## AIM:
Write a C program to read A values and check whether A is positive number or not.

# ALGORITHM:
1.	Declare a variable to store the input value A.
2.	Use the scanf function to read the value of A from the user.
3.	Check if the value of A is greater than zero.
4.	If A is greater than zero, print a message indicating that it's a positive number. 
5.	Otherwise, print a message indicating that it's not a positive number.
6.End the program.

# PROGRAM:

```
#include <stdio.h>

int main() { int A;

printf("Enter a value for A: ");
scanf("%d", &A);


if (A > 0) {
    printf("A is a positive number.\n");
} else {
    printf("A is not a positive number.\n");
}

return 0;
}
```
# OUTPUT:




![WhatsApp Image 2025-05-14 at 08 37 04_af766afb](https://github.com/user-attachments/assets/370d4b7c-ae65-4184-8bcd-85570e4b9587)







# RESULT:
Thus the program to read A values and check whether A is positive number or not has been executed successfully.
 
 
 


# EX-03- Operators-Expressions
## AIM:
Write a program to find minimum between two fraction numbers using conditional operator or ternary operator.

## ALGORITHM:
1.	Declare variables to store the two fraction numbers and the result.
2.	Use the printf function to prompt the user to enter the first fraction number (numerator and denominator separately).
3.	Use the scanf function to read the numerator and denominator of the first fraction.
4.	Repeat steps 2 and 3 to get the second fraction from the user.
5.	Calculate the decimal values of both fractions by dividing the numerators by the denominators.
6.	Use the conditional (ternary) operator to compare the decimal values and store the minimum value in the result variable.
7.	Print the minimum value.

## PROGRAM:

```
#include <stdio.h>

int main() { float num1, num2, min;

printf("Enter the first number: ");
scanf("%f", &num1);

printf("Enter the second number: ");
scanf("%f", &num2);


min = (num1 < num2) ? num1 : num2;


printf("The minimum number is: %.2f\n", min);

return 0;
}
```
## OUTPUT:





![WhatsApp Image 2025-05-14 at 08 37 04_a0942bac](https://github.com/user-attachments/assets/206aa502-a161-4670-947e-73483d8b73eb)




## RESULT:
Thus the program to find minimum between two fraction numbers using conditional operator or ternary operator has been executed successfully.




# EX-04- Using Conditional Statements

## AIM:
Write a C program to check whether the input value is equal to 1 using simple if statement

## ALGORITHM:
1.	Declare a variable to store the input value.
2.	Use the scanf function to read the input value from the user.
3.	Use an if statement to check if the input value is equal to 1.
4.	If the condition in the if statement is true, print a message indicating that the input value is equal to 1.
5.	Otherwise, print a message indicating that it's not equal to 1.
6.	End the program.

## PROGRAM:

```
#include <stdio.h>

int main() { int value;

printf("Enter a value: ");
scanf("%d", &value);

if (value == 1) 
{
    printf("The value is equal to 1.\n");
}

return 0;
}
   
```
## OUTPUT:


![WhatsApp Image 2025-05-14 at 08 37 04_da5d1696](https://github.com/user-attachments/assets/7c637773-bef1-4443-adc9-238e703b2865)







	

## RESULT:
Thus the program to check whether the input value is equal to 1 using simple if statement has been executed successfully



# EX-05- Calculating Total, Percentage, And Division Using Conditional Statements 
## AIM:
To write a C program that reads marks of three subjects, calculates the total and percentage, and then determines the division (First, Second, Pass, or Fail) based on the percentage and minimum marks criteria.
## ALGORITHM:
1.	Start
2.	Declare integer variables m1, m2, m3 for marks, and float variables tot, per.
3.	Input the marks for three subjects.
4.	Calculate total marks: tot = m1 + m2 + m3
5.	Calculate percentage: per = tot / 3
6.	Display total and percentage.
7.	Check if all marks are greater than or equal to 40:
8.	If yes:
a.	If percentage >= 60: Print “Division = First”
b.	Else if percentage >= 48: Print “Division = Second”
c.	Else if percentage >= 36: Print “Division = Pass”
9.	Else: Print “Division = Fail”
10.	End
## PROGRAM:

```
#include <stdio.h>

int main() { int M, N, i;

printf("Enter the starting value (M): ");
scanf("%d", &M);

printf("Enter the ending value (N): ");
scanf("%d", &N);

printf("Even numbers from %d to %d are:\n", M, N);

for (i = M; i <= N; i++)
{
    if (i % 2 == 0)
    {
        printf("%d ", i);
    }
}

printf("\n");

return 0;
}
```
## OUTPUT:



![WhatsApp Image 2025-05-14 at 08 37 30_fec35ee7](https://github.com/user-attachments/assets/9c5c1796-e151-4550-9b95-b14bd46189cd)

## RESULT:
The program successfully takes three subject marks, calculates the total and percentage, and correctly determines the division based on predefined grading logic.

