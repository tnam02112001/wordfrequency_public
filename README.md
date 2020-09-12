# Word Frequency Counter
Word Frequency Counter Program developed in C Programming Language

>⚠ Note: This is a programming project of the System Programming class (CPE 357) at Cal Poly. According to the Collaboration Agreement of the Institution regarding Code Distribution, I cannot make my source code of this project public. Please feel free to reach out to me if you need further access to this project.

## Features
Support input from both stdin and files
Support both binary and text files
Support inputs from multiple files
Utilizize Hash Table Data Structure with Separate Chaining for fast performance

## Usage
`./a.out [files…]`
By default, the program outputs to stdout:
* The number of unique words
* The total number of words
* Up to ten unique words with highest frequency
If input files are not provided, the program will read input from stdin

`./a.out [-nX]  [files]`
The program also supports the flag [-nX], in which X is the number of words with the highest frequency that the user wants to display.
