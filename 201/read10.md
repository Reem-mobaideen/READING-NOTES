# Error Handling in Javascript
If a JavaScript code generates an error, the error handling is to catches these errors and take appropriate action. The order in which statements are executed the most helpful way in error catching. Every statement in a script be in an execution contexts (in global context or function context or eval context). execution context that holds information about the environment within which the current code is being executed. Each execution context has its variables


# Understanding the Errors
If a JavaScript statement creates an error, then it throws an exception. At that point, the interpreter stops and looks for exception-handling error. Error objects can help you find where your mistakes are and browsers have tools to help you read them. Different type of errors may happen:
1.	Syntax Error: syntax is not correct
2.	Reference Error: variable does not exist
3.	Type Error: value is an unexpected data type
4.	Range Error: number is not in acceptable range


# Debugging 
Debugging is about deduction: eliminating potential causes of an error. Console of javascript tell us where there is an error in script and it is also displays the line where the problem. You can open the console window from any web browser windows (in chrome, firefox , etc)

![error eample from console](https://miro.medium.com/max/700/0*-IS8VjbpMT7I8p0D.png)