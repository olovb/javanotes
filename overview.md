
Overview
========

Types and Values
----------------

Java is __statically typed__ and __strongly typed__.

Every variable and every expression has a known type at the time of compilation. The types limit what values an expression can produce and operations on those values. 

There are two kinds of types: __primitive types__ and __reference types__.

There are two kinds of values: __primitive values__ and __reference values__.


Statements and Blocks
---------------------

A __statement__ forms a complete *unit of execution*. There are three kinds of statements.

The following types of expressions can be made into an __expression statement__ by terminating the expression with a semicolon:

- assignment expressions,
- any use of pre- or postfix operators `++` and `--`,
- method invocations, and
- object creation expressions.

There are two other kinds of statements: __declaration statements__ and __control flow statements__.

A __block__ is a group of zero or more statements between balanced braces. Blocks may be used anywhere a single statement is allowed.


Operators
---------

The operators have the following precedence:

- Postfix: `expr++` and `expr--`.
- Unary: `++expr`, `--expr`, `+expr`, `-expr`, `~`, and `!`.
- Multiplicative: `*`, `/`, and `%`.
- Additive: `+` and `-`.
- Shift: `<<`, `>>`, and `>>>`.
- Relational: `<`, `>`, `<=`, `>=`, and `instanceof`.
- Equality: `==` and `!=`.
- Bitwise AND: `&`.
- Bitwise exclusive OR: `^`.
- Bitwise inclusive OR: `|`.
- Logical AND: `&&`.
- Logical OR: `||`.
- Ternary: `? :`.
- Assignment: `=`, `+=`, `-=`, `*=`, `/=`, `%=`, `&=`, `^=`, `|=`, `<<=`, `>>=`, and `>>>=`.


Literals
--------

Special escape sequences for `char` and `String` literals: 

- `\b` (backspace), 
- `\t` (tab), 
- `\n` (line feed), 
- `\f` (form feed), 
- `\r` (carriage return), 
- `\"` (double quote), 
- `\'` (single quote), and 
- `\\` (backslash).


