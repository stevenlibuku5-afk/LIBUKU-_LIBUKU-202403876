ICT 202 Assignment – Infix Expression Converter

NAME: LIBUKU LIBUKU 

COURSE: ICT 202
STUDENT NO. 202403876

DESCRIPTON

This project implements a Java program that converts an infix expression into:

- Postfix notation
- Prefix notation

It demonstrates the use of stack data structures and operator precedence rules.

---
PROJECT STRUCTURE Project Structure

── InfixConversion.java   → Main Java program
── Assignment.docx     → Contains pseudocode + images
└── README.md


DOCUMENTATION FILE 

The file "documentation.txt" contains:

- Pseudocode for Infix to Postfix
- Pseudocode for Infix to Prefix
- Diagrams/images explaining the workflow


WORKFLOW OVERVIEW

1. Read the infix expression
2. Scan from left to right
3. Use a stack to manage operators
4. Apply precedence rules
5. Handle parentheses correctly
6. Generate postfix expression
7. Convert infix to prefix


PSEUDOCODE SUMMARY

INFIX TO POSTFIX

- Operands → added directly to output
- Operators → pushed to stack based on precedence
- Parentheses → control popping of operators

INFIX TO PREFIX

- Reverse the infix expression
- Swap parentheses
- Convert to postfix
- Reverse result to get prefix

IMAGES

All diagrams related to the workflow are included inside "Assignment.docx".

HOW TO RUN

1. Install Java (JDK)
2. Compile:
   javac InfixConversion.java
3. Run:
   java InfixConversion

 NOTES

- Supports operators: "+", "-", "*", "/"
- Handles parentheses correctly
- Input must be a valid infix expression

CONCLUSION
This project shows how stack-based algorithms can be used to convert expressions between infix, postfix, and prefix notations.
This project shows how stack-based algorithms can be used to convert expressions between infix, postfix, and prefix notations.
