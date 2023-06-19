# Lexical Analyzer

Lexical analyzer using an FSM

## Description

To write a lexical analyzer using an FSM. Using a function named lexer(), that returns a token when needed. The lexer should return a token and a lexeme. 
The program reads a file of source code, generates tokens, and outputs the results - printing both tokens and lexemes.

## Design

Using a struct for token type and using a vector for the Lexer. 3 major functions. A function to retrieve the state of the current element being analyzed. A vector to find the tokens. Finally, a function to retrieve the lexeme name.

Regular Expressions:
Letter = [a-zA-z]
Digit = [0-9]
Period = [.]
Under = [ _ ]

Integer = (digit)+
Real = (digit)(period)?(digit)
Identifier = (letter)(letter | digit | under)*


## Getting Started

### Dependencies

* Visual Studio 2019
* Windows 10

### Installing

* Open Visual Studio 2019
* Select - Clone or check out code
* In Repository Location enter: https://github.com/FernandoAndrade10/Calorie-Counting

### Executing program

* Install Visual Studio 2019. 
* Unzip launcher zip and lexical code zip. 
* Run the EXE called Lexical Launcher. 
* Make sure your test text file is in the proper path. 
* Enter your source code text file name and the program will start analyzing and outputting the tokens and lexemes.

### Year of Completion

2020

## Authors

Fernando Andrade f.andrade.8.10@gmail.com
