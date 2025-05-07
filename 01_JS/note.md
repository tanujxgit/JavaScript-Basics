# Variables and DataTypes in JavaScript

## Key Topics Covered

### 1. **Introduction to Variables**
   - Variables are used to store data in JavaScript.
   - Declaring variables using `var`, `let`, and `const`.
   - Differences between `var`, `let`, and `const`.

### 2. **Primitive Data Types**
   JavaScript has **seven** primitive data types:
   - **Number**: Represents numeric values.
   - **String**: Represents text values.
   - **Boolean**: Represents `true` or `false`.
   - **Undefined**: A variable that has been declared but not assigned a value.
   - **Null**: Represents an intentional absence of value.
   - **Symbol**: Introduced in ES6, used for unique identifiers.
   - **BigInt**: Used for handling large integers beyond `Number.MAX_SAFE_INTEGER`.

### 3. **Reference Data Types**
   - **Objects**: Collections of key-value pairs.
   - **Arrays**: Ordered collections of values.
   - **Functions**: First-class objects in JavaScript.
   - **Date**: Represents date and time.
   - **RegExp**: Represents regular expressions.

### 4. **Variable Scope**
   - **Global Scope**: Variables accessible throughout the script.
   - **Local Scope**: Variables declared inside a function.
   - **Block Scope**: Variables declared with `let` and `const` inside `{}`.

### 5. **Hoisting**
   - JavaScript moves variable declarations to the top of their scope.
   - `var` is hoisted with `undefined`, while `let` and `const` are hoisted but not initialized.

### 6. **Type Conversion**
   - Implicit conversion (Type coercion).
   - Explicit conversion using `Number()`, `String()`, `Boolean()`.

### 7. **Best Practices**
   - Use `const` for constants.
   - Use `let` for variables that change.
   - Avoid `var` due to scope issues.
   - Use meaningful variable names.
