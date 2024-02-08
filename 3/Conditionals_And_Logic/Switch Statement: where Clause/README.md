## Switch Statement: where Clause

### Introduction:

The where clause in a switch statement provides additional pattern matching capabilities by allowing conditions to be specified for individual cases. This is particularly useful when you need to check for specific conditions within each case.

### Syntax:

```swift
switch expression {
    case pattern where condition:
        // Code to execute if expression matches pattern and condition is true
    // More cases...
    default:
        // Default code to execute if expression does not match any case
}
```

## Instructions:

### Create Switch Statement:

Declare a switch statement with `wholeNumber` as its expression.

### Add Case Statements:

Inside the switch statement, create cases for checking whether `wholeNumber` is divisible by 2 and 3.
Use the `where` clause to specify conditions for each case.
Print "Composite" if the condition is met.
Add a default case to handle scenarios where `wholeNumber` is a prime number and print "Prime".

### Optional Challenge:

Generate a random integer between 10 and 20 using the `.random()` method and assign it to `wholeNumber`.
Print the value of `wholeNumber` to verify the generated number.

## Code Example:

```swift
var wholeNumber = Int.random(in: 10...20)
print("Random number:", wholeNumber)

switch wholeNumber {
  case let x where x % 2 == 0:
    print("Composite")
  case let x where x % 3 == 0:
    print("Composite")
  default:
    print("Prime")
}
```

## Explanation:

- The switch statement evaluates the value of `wholeNumber`.
- Each case checks if the value of `wholeNumber` meets specific conditions using the `where` clause.
- If `wholeNumber` is divisible by 2 or 3, it prints "Composite".
- If `wholeNumber` does not meet any conditions, it is considered a prime number and "Prime" is printed.
- The `.random()` method generates a random integer between 10 and 20, which is then assigned to `wholeNumber`.
- The value of `wholeNumber` is printed to verify the generated number.

Twitter: [Follow me for updates!](https://twitter.com/bhushcodes) 🐦
