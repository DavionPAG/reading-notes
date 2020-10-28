## JS Chapter 10: Debugging

- Order of execution is key
- Each function creates a new execution context.
- if you do not use the VAR keyword when creating a variable it is placed in global scope.
- When a statement needs data from another function, it stacks the new function on top of the current task.
- Looking up the stack can affect performance. It is ideal to create VARs in the function that uses them.
- When an Er ror object is created, it will contain the following properties: Name, message, fileNumber, lineNumber
- 7 types syntax error: Error, SyntaxError, ReferenceError, TypeError, RangeError, URIError, EvalError
- Backtracking and using console logs can help in deducing errors.
- Use more than one browser to help debug. You may get a variety of messages from each.
- console.info() is used for general information 
- console.warn() is used for warnings 
- console.error() can be used to hold errors 
- console.group() to group messages together. Good for related data.
- console.table() lets you output a table that shows: objects | arrays that contain other objects or arrays.
- You can pause the execution of a script on any line using breakpoints. Then hover over any elements to see the value of the variables to that point.
- You can set multiple breakpoints and 'step' through the code


---

- [Reading Notes Home](https://vektur.github.io/reading-notes/)