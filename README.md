# EX-NO-6-Pseudo-Random-Number

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:
1) Start the program and import the required libraries.
2) Seed the random number generator using the current time(i.e) rand(time(0));
3) Get the number of randon number to generate.
4) Pass the value for number of iterations and print the numbers.
5) End the program.
   
# PROGRAM:
```
Developed By: Muhammad Afshan A
Ref No.: 212223100035
```
```
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main() 
{
    int count, min, max;
    printf("Enter the number of random numbers to generate: ");
    scanf("%d", &count);
    printf("Enter the minimum value: ");
    
    scanf("%d", &min);
    printf("Enter the maximum value: ");
    scanf("%d", &max);
    srand(time(NULL));
    printf("Pseudorandom numbers:\n");   
    for (int i = 0; i < count; i++) 
    {
        int random_number = (rand() % (max - min + 1)) + min;
        printf("%d ", random_number);
    }
    return 0;
}
```

# OUTPUT:
<img width="750" alt="image" src="![image](https://github.com/user-attachments/assets/8c501a0b-5148-4be6-b481-a0f38c53ea5b)" />


# RESULT:
Thus the Implementation of Pseudorandom Number Generation Using Standard library has been done successfully.

