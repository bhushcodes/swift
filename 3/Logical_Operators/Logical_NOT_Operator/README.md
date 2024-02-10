# Logical NOT Operator in swift

The logical NOT operator, denoted by !, is a prefix operator used to negate or reverse the Boolean value of its operand. It flips true to false and false to true.

Here's how the logical NOT operator works:

- When applied to a true value, it returns false.
- When applied to a false value, it returns true.

Let's consider an example:

```swift
let a = true
let b = false

print(!a) // Prints: false
print(!b) // Prints: true
```

In this example, `!a` evaluates to false because the logical NOT operator negates the true value of `a`, and `!b` evaluates to true because it negates the false value of `b`.

The logical NOT operator can also be applied to expressions enclosed within parentheses. For instance:

```swift
print(!(true && false)) // Prints: true
```

Here, `true && false` evaluates to false, and applying the logical NOT operator (!) to false results in true.

Now, let's apply this concept to the given instructions:

1. In `NotOperator.swift`, there's a variable `feelingWell` that represents whether we're feeling well or not. Based on this variable, an if/else statement determines a course of action.

To place the given print statements in their correct code blocks:

- The print statement "Embrace the day!" should go inside the if block, which means it executes when `feelingWell` is true.
- The print statement "Have some vitamins and take care of yourself 🤒" should go inside the else block, which means it executes when `feelingWell` is false.

Here's the Swift code:

```swift
// Given variable
let feelingWell = false

// If/else statement
if feelingWell {
    print("Embrace the day!")
} else {
    print("Have some vitamins and take care of yourself 🤒")
}
```

If `feelingWell` is false, it will print "Have some vitamins and take care of yourself 🤒"; otherwise, it will print "Embrace the day!".

Twitter: [Follow me for updates!](https://twitter.com/bhushcodes) 🐦
