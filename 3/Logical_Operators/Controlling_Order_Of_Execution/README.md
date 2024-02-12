# Controlling the order of execution in swift

Controlling the order of execution of logical expressions is crucial for ensuring the intended outcome and readability of our code. We can use parentheses to explicitly specify the order in which operations should be performed, regardless of Swift's default operator precedence.

Consider the logical expression: `true || true && false && true`

Without parentheses, Swift evaluates this expression based on its default precedence rules, which prioritize the `&&` operator over `||`. So, the expression is evaluated as `(true || (true && false) && true)`, which results in `true`.

However, if we want to change the order of execution and group certain operations together, we can use parentheses. For example, `(true || true) && (false && true)`. Here, we've grouped the `||` operation and the `&&` operation separately with parentheses, ensuring that the `||` operation is evaluated first. This results in `true` because `(true || true)` is `true`, and `(false && true)` is `false`, and `true && false` is `false`.

In `Controlling_Order_Of_Execution.swift`, you're given multiple expressions where certain logical operators are missing. Your task is to add the logical operators (`&&` or `||`) in place of `___` to complete the expressions. Here's what you need to ensure:

- `bool1` and `bool2` should be `true`.
- `bool3` should be `false`.

Once you replace each `___` with the appropriate logical operator, any errors related to missing operators should disappear, and the code should execute correctly. This exercise helps reinforce the understanding of how to control the order of execution using parentheses and logical operators.

Twitter: [Follow me for updates!](https://twitter.com/bhushcodes) 🐦

Next: [Conditionals - Logical Operators - Cheatsheet](/3/Logical_Operators/Cheatsheet/README.md)
