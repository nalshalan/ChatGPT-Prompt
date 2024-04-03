<!-- Prompt -->
Can you explain to me clearly how to solve functions in JavaScript?

<!-- Response -->
Certainly! In JavaScript, functions are blocks of reusable code that perform a specific task. Functions can take inputs (parameters), perform operations, and return a result. Here's a step-by-step guide to working with functions in JavaScript:

1. **Function Declaration:**
   You can declare a function using the `function` keyword followed by the function name and parentheses containing any parameters the function should accept. For example:

   ```javascript
   function greet(name) {
       return "Hello, " + name + "!";
   }
   ```

2. **Function Expression:**
   Another way to define a function is by using a function expression. This involves assigning a function to a variable. For example:

   ```javascript
   var greet = function(name) {
       return "Hello, " + name + "!";
   };
   ```

3. **Function Invocation:**
   Once a function is declared, you can call (invoke) it by using its name followed by parentheses. If the function expects parameters, you provide them within the parentheses. For example:

   ```javascript
   console.log(greet("John")); // Output: Hello, John!
   ```

4. **Return Statement:**
   Functions can return values using the `return` keyword. When a function encounters a `return` statement, it immediately stops executing and returns the specified value. For example:

   ```javascript
   function add(a, b) {
       return a + b;
   }
   ```

5. **Parameters:**
   Functions can accept parameters, which are placeholders for values that will be passed to the function when it's invoked. Parameters are listed within the parentheses in the function declaration. For example:

   ```javascript
   function multiply(x, y) {
       return x * y;
   }
   ```

6. **Arguments:**
   When you call a function, you provide actual values called arguments for its parameters. These arguments are passed in the same order as the parameters. For example:

   ```javascript
   console.log(multiply(3, 4)); // Output: 12
   ```

7. **Scope:**
   Functions have their own scope. Variables declared inside a function are local to that function and are not accessible from outside. Variables declared outside of any function are global and can be accessed from anywhere in the code.

8. **Arrow Functions (ES6):**
   In modern JavaScript, you can also use arrow functions, which provide a more concise syntax. For example:

   ```javascript
   const square = (x) => x * x;
   ```

   This is equivalent to:

   ```javascript
   function square(x) {
       return x * x;
   }
   ```

These are the basics of working with functions in JavaScript. As you get more comfortable, you can explore more advanced concepts like higher-order functions, closures, and function hoisting.