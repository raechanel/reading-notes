# In Memory Stage

***

## Review Based on [The JavaScript Call Stack - What It Is and Why It's Necessary](https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4/)

**What is a ‘call’?**

A data structure that uses the Last In, First Out (LIFO) principle to temporarily store and manage function invocation (call).

**How many ‘calls’ can happen at once?**

One

**What does LIFO mean?**

The last function that gets pushed into the stack is the first to be pop out, when the function returns.

**Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.**


**What causes a Stack Overflow?**

When there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accommodate before throwing a stack error.

## Review Based on [JavaScript error messages && debugging](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)

**What is a ‘reference error’?**

When you try to use a variable that is not yet declared you get this type os errors.

**What is a ‘syntax error’?**

This occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.

**What is a ‘range error’?**

Try to manipulate an object with some kind of length and give it an invalid length and this kind of errors will show up.

**What is a ‘type error’?**

This types of error show up when the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.

**What is a breakpoint?**

The breakpoint can also be achieved by putting a debugger statement in your code in the line you want to break

**What does the word ‘debugger’ do in your code?**

Debugs the code / Figures out why/what is stopping your code from working

### Other Reading Notes

* [Home](README.md)
* [Introduction to React and Components](class-1.md)
* [States and Props](class-2.md)
* [Passing Functions as Props](class-3.md)
* [React and Forms](class-04.md)
* [Putting It All Together](class-5.md)
* [Node.js](class-6.md)
* [Rest](class-7.md)
* [APIs](class-8.md)
* [Functional Programming](class-9.md)
* [Things I want to know more about](questions.md)
