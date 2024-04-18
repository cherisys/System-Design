### What are Object-Orientation Abusers?
These smells are incomplete or incorrect application of object-oriented programming principles. 

## 1. Switch Statements
You've a complex switch operator or sequence of **if** statements.

## 2. Temporary Field
Temporary fields get their values and thus are needed by objects only under certain circumstances. Outside of these circumstances they are empty.

## 3. Refused Bequest
If subclasses uses only some of the methods or properties inherited from its parents, the hierarchy is off-kilter. Unneeded methods simply go unused or be redefined and give off exceptions.

## 4. Alternative Classes with Different Interfaces
Two classes perform identical functions but have different method names.

