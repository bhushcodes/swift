# Swift Conditionals: Introduction

## Overview:
Conditionals are fundamental to programming as they allow a program to make decisions based on certain conditions. In Swift, conditionals are implemented through conditional statements and operators, providing the ability to react to different scenarios.

## Use Cases:
- Making decisions based on user input.
- Handling authentication processes.
- Reacting to changes in data or environment.

## Key Concepts:
- **if Statement:** Executes a block of code only if a specified condition is true.
- **else Statement:** Executes a block of code if the condition specified in the if statement is false.
- **else if Statement:** Allows for additional conditions to be checked if the initial if condition is false.
- **Logical Operators:** `&&` (logical AND), `||` (logical OR), `!` (logical NOT), used to create complex conditions.
- **Comparison Operators:** `==` (equal), `!=` (not equal), `<` (less than), `>` (greater than), `<=` (less than or equal to), `>=` (greater than or equal to), used to compare values.

## Example:

```swift
var temperature = 25

if temperature > 30 {
    print("It's a hot day!")
} else if temperature >= 20 && temperature <= 30 {
    print("The weather is just right.")
} else {
    print("It's a bit chilly.")
}
```
## Explanation:
- Checks the temperature and prints a message based on different conditions.
- Demonstrates the use of if, else if, and else statements.
- Introduces logical operators (`&&`) for complex conditions.

In the upcoming lessons, we will delve deeper into Swift's conditional statements and explore their applications in various scenarios.

Twitter: [Follow me for updates!](https://twitter.com/bhushcodes) 🐦

Next: [Conditionals - Introduction to Conditionals](/3/Conditionals_And_Logic/If_Statement/README.md)
