# EX-05 Program to Check Whether a Character is a Digit or Not

## AIM:
To write a C program that reads a character from the user and checks whether it is a digit or not.

## ALGORITHM:

1. Start
2. Declare a variable ch of type char.
3. Read a character from the user using scanf("%c", &ch).
4. Use the function isdigit(ch) from <ctype.h> to check if the character is a digit.
5. If isdigit(ch) returns true, print "The entered character is a digit."
6. Else, print "The entered character is not a digit."
7. Stop

## PROGRAM:
```
#include <stdio.h>
#include <ctype.h>

int main()
{
    char ch;
    printf("Enter the character: ");
    scanf("%c",&ch);
    if(isdigit(ch))
    {
        printf("The entered character is a digit.");
    }
    else
    {
        printf("The entered character is not a digit.");
    }
}
```

## OUTPUT:
<img width="661" height="126" alt="image" src="https://github.com/user-attachments/assets/4be39ac7-a2ea-44bf-b995-d24e3abe0189" />


## RESULT:
The program successfully reads a character from the user and determines whether it is a digit or not using conditional checks
