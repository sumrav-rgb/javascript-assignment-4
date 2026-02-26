Task 2:- 
The doSomething() function takes 60 seconds to execute. Each await runs one after another, so the times add up: 11 + 44 + 4 = 59 seconds, plus approximately 1 second for calling doSomethingElse() at the end, giving a total of 60 seconds.
