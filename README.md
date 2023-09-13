# 'let' and 'const' exercise
- ### What is the difference between var and let?
    - The difference between 'var' and 'let' is that 'var' is reassignable variable, while 'let' cannot be reassigned. They are both mutable types however. The 'var' keyword is function scoped while 'let' is block scoped.

- ### What is the difference between 'var' and 'const'?
    - The difference between 'var' and 'const' is that var can be reassigned and can be changed from its initial declaration. 'const' is an immutable type and has to declared with a value before it's able to be used.

- ### What is the difference between 'let' and 'const'?
    - The difference between 'let' and const is that 'let' can be mutated from it's original value, 'const' on the other hand cannot

- ### What is hoisting?
    - Hoisting is JavaScripts way of compiling 'var' types. You can imagine when the program is run it compiles 'var' types first. When you run a function (eg. console.log(variable)) and then declare it afterwards (var variable = 'chickens') JavaScript compiles and assigns the 'var' first and then runs the console.log which will return 'undefined'
