## Ebror Handling & Debugging

### JavaScript can be hard to learn and everyone makes mistakes when writing it. This chapter will help you learn how to find the errors in your code. It will also teach you how to write scripts that deal with potential errors gracefully.

## ORDER OF EXECUTION
### To find the source of an error, it helps to know how scripts are processed. The order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run: see table in 452

## EXECUTION CONTEXTS
### The JavaScript interpreter uses the concept of execution contexts. There is one global execution context; plus, each function creates a new new execution context. They correspond to variable scope.

## Stack : js iterpreter process one line pf code  at a time
## UNDERSTANDING SCOPE 
### In the interpreter, each execution context has its own va ri ables object. It holds the variables, functions, and parameters available within it. Each execution context can also access its parent's v a ri ables object.

## some ipmortant note : 
1. If you understand execution contexts (which have two stages) and stacks, you are more likely to find the error in your code.
2. Debugging is the process of finding errors. It involves a process of deduction.
3. The console helps narrow down the area in which the error is located, so you can try to find the exact error.
4. JavaScript has 7 different types of errors. Each creates its own error object, which can tell you its line number and gives a description of the error.
5. If you know that you may get an error, you can handle it gracefully using the try, catch, finally statements. Use them to give your users helpful feedback. 