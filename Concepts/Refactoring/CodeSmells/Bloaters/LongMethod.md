# Long Method?

## Signs & Symptoms
A method contain too many lines of code. Generally, any method longer than 10 lines of code should make you start questioning.

## Reason for the problem
It's easier to write code than to read it, this smell remain unnoticed until the method turns into an ugly, oversized beast.

## Treatment
If you feel the need to comment on something inside a method, you should take this code and put it in new method. Even a single line can and should be split into a separate method, if it requires explanations.
> * To reduce the length of a method body, use **Extract Method**.
> * If local variables and parameters interfere with extracting a method, use **Replace Temp with Query**, **Introduce Parameter Object**, or **Preserve Whole Object**.
> * If none of previous recipes help, try moving the entire method to a separate object via **Replace Method with Method Object**.
> * Conditional operators and loops are good clue that code can be moved to a separate method. For conditionals, use **Decompose Conditional**. If Loops are in the way, try **Extract Method**.


## Payoff
* Among all types of object-oriented code, classes with short methods live longest. The longer a method is the harder it becomes to understand and maintain.
* In addition, long methods offer perfect hiding place for unwanted duplicate code.

## Performance
* Impact of increase in the number of methods on performance is negligible and not worth worrying about.
* Now you've clear and understandable code, you're more likely to find truly effective methods for restructuring code and getting real performance gains if the need arises.