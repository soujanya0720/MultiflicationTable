# MultiflicationTable
A simple program to print the multiplication table of a given number. This project helps beginners understand loops, user input, and basic arithmetic operations.

##  About the Project

The Multiplication Table Program is a simple beginner-friendly project that prints the multiplication table of a number entered by the user. It helps beginners understand loops, user input, and basic arithmetic operations.

##  Features

* Accepts a number from the user.
* Displays the multiplication table from 1 to 10.
* Uses a `for` loop to perform repeated calculations.
* Simple and easy-to-understand code.

##  Technologies Used

* C Programming
* Standard Input/Output (`stdio.h`)

##  Source Code

```c
#include <stdio.h>

int main() {
    int n, i;

    printf("Enter a number: ");
    scanf("%d", &n);

    for (i = 1; i <= 10; i++) {
        printf("%d x %d = %d\n", n, i, n * i);
    }

    return 0;
}
```

##  How to Run

1. Download or clone this repository.
2. Open the source code in a C compiler or IDE.
3. Compile and run the program.
4. Enter a number to display its multiplication table.

##  Sample Output

text
Enter a number: 5
5 x 1 = 5
5 x 2 = 10
5 x 3 = 15
5 x 4 = 20
5 x 5 = 25
5 x 6 = 30
5 x 7 = 35
5 x 8 = 40
5 x 9 = 45
5 x 10 = 50

##  Learning Outcomes

* Understanding `for` loops.
* Taking input from the user.
* Performing multiplication operations.
* Displaying formatted output.


This project is open-source and available for educational and learning purposes.
