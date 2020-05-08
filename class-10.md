# JavaScript book, Ch. 10, “Error Handling & Debugging”


Knowing how the computer executes and in what order helps when debugging because lets say a function doesn't execute you know where to start looking.

Also knowing how to use the dev can console tools in the browser can tell you errors and also let you try out fixes without typing into you code.

### The Three Execution Contexts (JS)
- Global Context: code in the script that's not in a function (only one golbal context in any page)
- Function Context: code in a function (functions have their own context)
- _Eval Context: text executed like code in an internal function (haven't learned yet)._

You can use console.logs to comunicate with the sonsole in the browser to get hints to where your code has gone wrong.

### Variable Scope
- Global: declared outside functions so it can be used anywhere 
- Function-Level or Local: declared within function so it can only be used there

## Error Objects
> Error objects tell you name: type of execution, message: description, file number: which file, and line number in said file.
- Error: Generic, the other errors are based off this one
- Syntax: syntax has not been followed
- Reference: couldn't reference varible because it wasn't declared or not in scope
- Type: unexpected data type that can't be coerced
- Range: numbers not in accepted range
- URI: encodeURI(), decodeURI(), and similar methods incorrectly used
- _Eval:eval() function incorrectly used_
