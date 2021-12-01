# Java Testcase Runner

## Introduction

This application is a runner to run java programs and perform comparisons against a given test case. The program was developed on the bash language and can run via the command line, especially on Unix-based computers such as Linux and macOS.

## Pre-requisite

 - Command line / Terminal
 - bash
 - diff

## How to use

1. Clone or download this repository
2. Enter your test case folder in the "src/testcase/" directory
3. Make sure the input file starts with "in_*.txt" and the expected output file begins with "out_*.txt". An example for TP3 is already in the template
4. Run your program on the working file (in this case the program file is named "TP3.java"
5. Run the program via the command line by running the command "src /run"

## Read the output from

This program produces two outputs, namely "AC" and "WA". If the test case outputs "AC", it means that your output is as expected in the test case. If "WA" means your program is still wrong and will issue your error location.