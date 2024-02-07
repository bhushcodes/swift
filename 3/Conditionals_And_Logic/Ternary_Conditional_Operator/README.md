## Swift Ternary Conditional Operator

### Introduction:

In Swift, the ternary conditional operator (`? :`) offers a shorter, more concise alternative to a standard if/else statement. It executes one of two expressions depending on the boolean result of the condition.

### Instructions:

#### Rewrite Conditional in Ternary Format:

Rewrite the existing if/else statement in ternary format on the following line.

### Code Example:

```swift
var isWindy = true

// Standard if/else statement
if isWindy {
    print("It's windy!")
} else {
    print("It's calm.")
}

// Ternary conditional operator format
isWindy ? print("It's windy!") : print("It's calm.")
```

### Explanation:

- The program initially checks the value of the `isWindy` variable using a standard `if/else` statement and prints a message accordingly.
- Then, the program rewrites the same logic using the ternary conditional operator.
- In the ternary format, the condition `isWindy` is evaluated, and if it's true, "It's windy!" is printed; otherwise, "It's calm." is printed.

By using the ternary conditional operator, we achieve the same result with a shorter and more concise syntax. However, it's essential to use this operator judiciously to maintain code readability.

Twitter: [Follow me for updates!](https://twitter.com/bhushcodes) 🐦
