# What is Technical Debt?
If you get a loan, this allows you to make purchases faster. You pay extra for expediting the process. You can even rack up so much interest that the amount of interest exceeds your total income, making full payment impossible.

Same thing can happen with code. You can temporarily speed up without writing tests for new features, but this will gradually slow your progress everyday until you eventually pay off the debt by writing tests.

## Causes of Technical Debt

> ### Business pressure 
> Business might force you to roll out features before they're completely finished. In this case, **patches** and **kludges** will appear in the code to hide the unfinished parts of the project.

> ### Lack of understanding of the consequences of Technical Debt
> Sometimes employers doesn't understand that technical debt has **interest**, in long run it slows down the pace of development as debt accumulates. This can make it difficult to dedicate team's time to refactoring because management doesn't see the value of it.

> ### Failing to combat strict coherence of components
> When project is monolith, any changes to one part will affect others. Team development is made more difficult because it's difficult to isolate the work of individual members.

> ### Lack of tests
> Lack of immediate feedback encourages quick, but risky workarounds or kludges. In worst cases, these changes are implemented and deployed right into the production without any prior testing. The consequences can be catastrophic.

> ### Lack of documentation
> Slows down the introduction of new people to the project and can grind development to a halt if key people leave the project.

> ### Lack of interaction between team members
> If knowledge base is not distributed througout the company, people will end up working with an outdated understanding of processes and information about the project. This situation can be exacerbated when junior developers are incorrectly trained by their mentors.

> ### Long-term simultaneous development in several brances
> It leads to the accumulation of technical debt, which is increased when changes are merged. The more changes made in isolation, the greater the total technical debt.

> ### Delayed refactoring
> Project's requirements are constantly changing, at some point of time it becomes obvious that parts of code are obsolete, have become cumbersome, and just be redesigned to meet new requirements.
>
>On the other hand, programmers are writing new code everyday that works with obsolete parts. Therefore, the longer refactoring is delayed, the more dependent code will have to be reworked in future.

> ### Lack of compliance monitoring
> Happens when everyone writes code as they see fit, without any standards or guidelines in place.

> ### Incompetence
> This is when the developer just doesn't know how to write decent code.