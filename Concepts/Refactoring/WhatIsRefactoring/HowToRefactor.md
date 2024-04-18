### How to Refactor
Refactoring should be done as a series of small changes, each of which makes the exiting code slightly better while still leaving the program in working order.

### Checklist of refactoring done "right way"

> ## Code should become cleaner
>* If code remains unclean after refactoring, try to figure out why this happened.
>* It happens when you move away from refactoring with small changes and mix a whole bunch of refactorings into one big change. Easy to lose your mind, especially if you've a time limit.
>* It can also happen when working with extremely sloppy code. Whatever you improve, the code as a whole remains a disaster. In this case, it's worthwhile to completely rewriting parts of the code, but before that you should have written tests and set aside a good chunk of time.

> ## New functionality shouldn't be created
>* Don't mix refactoring and direct development of new features.
>* Try to separate these processes at least within the confines of individual commits.

> ## All existing tests must pass
>* There are two cases when tests can breakdown after refactoring:
>   **1. You made an error during refactoring:** go ahead and fix the error.
>   **2. Your tests were too low-level:** for example, you were testing private methods of classes. You can either refactor the tests themselves or write an entirely new set of higher-level tests. A great way to avoid this kind of situation is to write **BDD-Style Tests (Behavioral Driven Development Style Tests)**.