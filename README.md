# **Compiler-Python**

## Authors 

Olgierd Smyka, Hubert Kasprzycki

## Overview
This project is a compiler for a pseudocode language supporting basic arithmetic and matrix operations, built using the SLY (Simple Lex-Yacc) library. It includes a scanner, parser, AST (Abstract Syntax Tree), basic semantic analysis, and an interpreter for executing pseudocode in Python. The focus was on learning compiler construction and implementing fundamental optimizations for mathematical expressions.

## Usage

To run the compiler and execute a pseudocode program, provide a file containing the pseudocode using the following command:
```bash
python main.py <filename>
```
If no filename is provided, the default file "samples/lab5/fibonacci.m" will be used.

Additional example pseudocode files for testing can be found in the [samples](samples/) directory.

## Setup

### Windows
```bash
python -m venv env
.\env\Scripts\activate
pip install -r requirements.txt
```

### Linux
```bash
python3 -m venv env
source env/bin/activate
pip install -r requirements.txt
```
