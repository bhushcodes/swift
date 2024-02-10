# Logical OR Operator in swift

The logical OR operator, denoted by ||, evaluates two operands and returns a Boolean result. It returns true if at least one of the operands is true, and false only if both operands are false.

Here's the truth table for the logical OR operator:

| Operand 1 | Operand 2 | Result |
| --------- | --------- | ------ |
| true      | true      | true   |
| true      | false     | true   |
| false     | true      | true   |
| false     | false     | false  |

In Swift, the logical OR operator is represented by two pipe symbols: ||.

Let's consider an example:

```swift
var snowing = false
var raining = true

if snowing || raining {
    print("Wear waterproof shoes!")
}
```

In this example, we're checking if it's snowing OR raining. If either condition is true, we advise wearing waterproof shoes. Since raining is true in this case, the condition evaluates to true, and the message "Wear waterproof shoes!" will be printed.

Now, let's apply this concept to the instructions:

1. We're given two variables: `carInMotion` initialized to `false` and `insideACar` initialized to `true`.

2. We create an if statement that checks the Boolean result of `carInMotion` OR `insideACar`. This means that if the car is in motion OR if the person is inside a car, we'll print a safety message.

Here's the Swift code for the given instructions:

```swift
// Declare variables
var carInMotion = false
var insideACar = true

// Check if the car is in motion or if the person is inside a car
if carInMotion || insideACar {
    // Print safety message
    print("Safety first! Buckle up.")
}
```

This code will print "Safety first! Buckle up." because the condition `carInMotion || insideACar` evaluates to true, since `insideACar` is true.

Twitter: [Follow me for updates!](https://twitter.com/bhushcodes) 🐦

Next: [Conditionals - Logical Operators - Logical NOT Operator](/3/Logical_Operators/Logical_NOT_Operator/README.md)
