### What are Bloaters?
Bloaters are code, methods, and classes that have increased to such gargantuan proportions that they are hard to work with. 

## 1. Long Method
A method contain too many lines of code. Generally, any method longer than 10 lines of code should make you start questioning.

## 2. Long Class
A class contain many fields, methods, or lines of code.

## 3. Long Parameter List
More than 3 or 4 parameters for a method.

## 4. Data Clumps
* Sometimes different parts of code contain identical groups of variables, i.e. parameters to connect to database.
* These clumps should be turned into their own classes.

## 5. Primitive Obsession
* Use of primitives instead of small object for simple tasks, i.e. currency, ranges, special strings for phone numbers etc.
* Use of constants for coding information, i.e. USER_ADMIN_ROLE = 1 for referring to users with Admin Rights.
* Use of string constants as field names to use in data arrays.
