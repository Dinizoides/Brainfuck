# Brainfuck

Brainfuck is one of the most famous esoteric programming languages, created in 1993 by Urban Müller, and has inspired the creation of a host of other languages. Due to the fact that the last half of its name is often considered one of the most offensive words in the English language. This can make it a bit difficult to search for information regarding brainfuck on the web, as the proper name might not be used at all in some articles.

## Language overview

Brainfuck operates on an array of memory cells, each initially set to zero. (In the original implementation, the array was 30,000 cells long, but this may not be part of the language specification; different sizes for the array length and cell size give different variants of the language). There is a pointer, initially pointing to the first memory cell. The commands are:

| Command | Description |
| ------ | ------ |
| > | Move the pointer to the right |
| < | Move the pointer to the left |
| + | Increment the memory cell at the pointer |
| - | Decrement the memory cell at the pointer |
| . | Output the character signified by the cell at the pointer |
| , | Input a character and store it in the cell at the pointer |
| [ | Jump past the matching ] if the cell at the pointer is 0 |
| ] | Jump back to the matching [ if the cell at the pointer is nonzero |

All characters other than `><+-.,[]` should be considered comments and ignored.
