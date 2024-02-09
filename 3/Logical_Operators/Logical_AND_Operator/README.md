# Logical AND Operator in swift

The logical AND operator (`&&`) is used to combine two conditions in a logical expression. It evaluates to true if and only if both operands are true; otherwise, it evaluates to false. Here's a breakdown of the logical AND operator:

- **Truth Table**: The truth table shows all possible outcomes of the `&&` operator:

| Operand 1 | Operand 2 | Result |
| --------- | --------- | ------ |
| true      | true      | true   |
| true      | false     | false  |
| false     | true      | false  |
| false     | false     | false  |

- **Symbol**: The logical AND operator is denoted by two ampersand symbols (`&&`) and translates to "AND".

- **Example**: In the provided example, assume we have two conditions:

  - `time >= 8`: Checks if the current time is 8 PM or later.
  - `phoneInUse`: Checks if the phone is in use.

  The `if` statement uses the `&&` operator to combine these conditions. If both conditions are true, indicating that it is 8 PM or later and the phone is in use, the brightness is set to 0.75 (dimmed). Otherwise, if at least one condition is false, the brightness remains at 1 (normal).

- **Usage**: The logical AND operator is commonly used in conditional statements (`if`, `while`, etc.) to execute a block of code only when multiple conditions are simultaneously met.

**Instructions**:

1. In the `NewYear.swift` file, there are two variables declared: `midnight` and `date`.
2. You need to create an `if` statement that checks if it is midnight and the date is "January 1, 2020".
3. If both conditions are true, print the message "It's the start of a new decade!".
4. Test your code with different values for `midnight` and `date` to ensure it behaves as expected.

Twitter: [Follow me for updates!](https://twitter.com/bhushcodes) 🐦
