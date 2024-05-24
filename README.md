# C program to find number of years based on principle, rate & simple interest.
## AIM:
To Write a C program to find number of years based on principle, rate & simple interest.
## ALGORITM:
1. Include the standard input-output header file.
2. Define the main function.
3. Declare variables to store the principle amount, rate of interest, and simple interest.
4. Prompt the user to enter the principle amount and read the input.
5. Prompt the user to enter the rate of interest and read the input.
6. Prompt the user to enter the simple interest and read the input.
7. Calculate the number of years using the formula: number of years = (simple interest * 100) / (principle * rate).
8. Print the result as the number of years.
## PROGRAM:
```
#include <stdio.h>
int main()
{
    float p,r, i,yr;
    scanf("%f",&p);
    scanf("%f",&r);
    scanf("%f",&i);
    yr=(i/(p*r))*100;
    printf("No.of.Year is = %.2f",yr);
    return 0;
}
```
## OUTPUT:
![image](https://github.com/VerginJenifer/c-programming-11/assets/136251012/e2d58f83-5209-47f1-a220-29c7bae8799e)

## RESULT:
Thus, C program to find number of years based on principle, rate & simple interest was executed successfully.



