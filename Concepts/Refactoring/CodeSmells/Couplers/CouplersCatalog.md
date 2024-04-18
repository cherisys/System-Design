### What are Couplers?
Smells in this group contribute to excessive coupling between classes, or show what happens if coupling is replaced by excessive delegation. 

## 1. Feature Envy
A method accesses data of another object more than its own data.

## 2. Message Chains
In code you see a series of calls resembling **$a->b()->c()->d()**

## 3. Middle Man
If a class only does the delegation of work to another class, why does it exists at all?

## 4. Inappropriate Intimacy
One classes uses the internal fields or methods of another class.

## 5. Incomplete Library Class
Sooner or later libraries stop meeting user needs. Only solution to the problem - changing the library - is often impossible since the library is read-only.
