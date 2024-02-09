# Logical Operators in Swift:

Logical operators in Swift are used to combine or modify boolean values (true or false). There are three main logical operators:

### AND (&&):

The AND operator (&&) returns true if both operands are true, otherwise, it returns false.
Truth table:

```swift
true && true   -> true
true && false  -> false
false && true  -> false
false && false -> false
```

### OR (||):

The OR operator (||) returns true if at least one of the operands is true, otherwise, it returns false.
Truth table:

```swift
true || true   -> true
true || false  -> true
false || true  -> true
false || false -> false
```

### NOT (!):

The NOT operator (!) is a unary operator that negates the value of its operand. If the operand is true, ! converts it to false, and if the operand is false, ! converts it to true.
Example: !true evaluates to false, and !false evaluates to true.

#### Example Usage:

```swift
let x = true
let y = false

let result1 = x && y  // false (true && false)
let result2 = x || y  // true (true || false)
let result3 = !x      // false (!true)
```

### Explanation:

- In the example, `result1` evaluates to false because `x` is true and `y` is false, so the AND operation returns false.
- `result2` evaluates to true because `x` is true, and in an OR operation, if any operand is true, the result is true.
- `result3` evaluates to false because the NOT operator negates the value of `x`, which is true.

**Note:**
Logical operators are frequently used in conditional statements (`if`, `else`, `while`, etc.) to control the flow of execution based on boolean conditions. They are essential for writing complex decision-making logic in programs.

Twitter: [Follow me for updates!](https://twitter.com/bhushcodes) 🐦

Next: [Conditionals - Logical Operators - Logical And Operator](/3/Logical_Operators/Logical_AND_Operator/README.md)
