# CD-Mini-Compiler

This Mini Compiler is Built for Python and handles the If-Elif-Else and the While Constructs.

ARCHITECTURE OF THE LANGUAGE

The term compilation denotes the conversion of an algorithm expressed in a human-oriented source language to an equivalent algorithm expressed in a hardware-oriented target language. As we all know Python has a very flexible syntax and hence we have tried as much as possible to incorporate python into the grammar. 

In this process of incorporating python into the grammar there are few things we could not take care of like: semicolons, so a semicolon will result in an error while parsing. All lines of code terminate upon seeing a newline character. 
These are function we have implemented:
● If-Elif-Else and While constructs 
● Print Statements
● pass, break and void returns
● Function definitions and Calls
● Lists
● All arithmetic operators and all boolean operators except standalone ‘!’  (“!=” is taken care of)
● Single Line Comments (#)

Semantically we have checked the following :
● Whether any variable used on the RHS is defined and in the current scope or any Enclosing Scope of the current scope.
● Whether a variable being indexed is List
● Whether all expressions in the If and While Clauses are Boolean expressions

This project was done by a team of 3 : Tejus, Manjunath and Myself
