### What are Code Smells?
Code smells are indicators of problems that can be addressed during refactoring. Code smells are easy to spot and fix, but they may be just symptoms of a deeper problem within code.

## 1. Bloaters
Bloaters are code, methods, and classes that have increased to such gargantuan proportions that they are hard to work with. 
> 1. Long Method
> 2. Large Class
> 3. Long Parameter List
> 4. Primitive Obsession
> 5. Data Clumps

## 2. Object-Orientation Abusers
Incomplete or incorrect application of object-oriented programming principles. 
> 1. Switch Statements
> 2. Temporary Field
> 3. Refused Bequest
> 4. Alternative Classes with Different Interfaces

## 3. Change Preventors
If you've to make a change in one place in your code, you've to make many changes in other places too. 
> 1. Divergent Change
> 2. Shotgun Surgery
> 3. Parallel Inheritance Hierarchies

## 4. Dispensables
Something pointless and unneeded whose absence would make code cleaner, efficient and easier to understand. 
> 1. Comments
> 2. Duplicate Code
> 3. Data Class
> 4. Dead Code
> 5. Lazy Class
> 6. Speculative Generality

## 5. Couplers
Excessive coupling between classes, or what happens if coupling is replaced by excessive delegation. 
> 1. Feature Envy
> 2. Message Chains
> 3. Middle Man
> 4. Inappropriate Intimacy
> 5. Incomplete Library Class
