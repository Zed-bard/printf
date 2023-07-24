# 0x11. C - printf
### DEFINITION OF TERMS
In C programming, printf is a standard library function used to print formatted output to the console or file. It stands for "print formatted" and is part of the stdio.h header file. The printf function allows you to specify a format string that contains placeholders for variables or values that you want to display.
## GENERAL REQUIREMNTS
 - Allowed editors: vi, vim, emacs
 - All files will be compiled on Ubuntu 20.04 LTS using gcc with the options -Wall -Werror -Wextra -pedantic -std=gnu89
 - All files should end with a new line
 - A README.md file at the root of the project folder is mandatory
 - Code should follow the Betty style, checked using betty-style.pl and betty-doc.pl
 - No use of globa
## OVERVIEWS OF THE PROJECTS
The main goal of the project outlined in the bellow table is to create a function that can handle various conversion specifiers and custom conversion specifiers to produce formatted output. The function should be able to handle signed and unsigned integers in different formats (**decimal, octal, hexadecimal**), **print strings**, and **pointers**. It should also handle flag characters, length modifiers, field width, precision, and various combinations of these requirements. Additionally, the function should strive for performance optimization by using a local buffer to reduce the number of calls to the write system call. Ultimately, the project aims to ensure that all the specified options work well together.
### Table of contents
| Number | Question | Description |
|--------|----------|-------------|
| 0      | I'm not going anywhere. You can print that wherever you want to. I'm here and I'm a Spur for life | Write a function that produces output according to a format. |
| 1      | Education is when you read the fine print. Experience is what you get if you don't | Handle the following conversion specifiers |
| 2      | With a face like mine, I do better in print | Handle the following custom conversion specifiers |
| 3      | What one has not experienced, one will never understand in print | Handle the following conversion specifiers |
| 4      | Nothing in fine print is ever good news | Use a local buffer of 1024 chars in order to call write as little as possible |
| 5      | My weakness is wearing too much leopard print | Handle the following custom conversion specifier |
| 6      | How is the world ruled and led to war? Diplomats lie to journalists and believe these lies when they see them in print | Handle the following conversion specifier: p |
| 7      | The big print gives and the small print takes away | Handle the following flag characters for non-custom conversion specifiers |
| 8      | Sarcasm is lost in print | Handle the following length modifiers for non-custom conversion specifiers: l, h |
| 9      | Print some money and give it to us for the rain forests | Handle the field width for non-custom conversion specifiers |
| 10     | The negative is the equivalent of the composer's score, and the print the performance | Handle the precision for non-custom conversion specifiers |
| 11     | It's depressing when you're still around and your albums are out of print | Handle the 0 flag character for non-custom conversion specifiers |
| 12     | Every time that I wanted to give up, if I saw an interesting textile, print whatever, suddenly I would see a collection | Handle the - flag character for non-custom conversion specifiers |
| 13     | Print is the sharpest and the strongest weapon of our party | Handle the following custom conversion specifier |
| 14     | The flood of print has turned reading into a process of gulping rather than savoring | Handle the following custom conversion specifier |
| 15     | * | All the above options work well together |
