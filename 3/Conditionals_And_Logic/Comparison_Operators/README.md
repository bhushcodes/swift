## Swift Comparison Operators

### Introduction:

Comparison operators in Swift are used to compare two values and determine their relationship, returning a Boolean result. These operators are fundamental for creating conditions and making decisions based on specific criteria.

### Supported Comparison Operators:

- `==`: Equal to
- `!=`: Not equal to
- `>`: Greater than
- `<`: Less than
- `>=`: Greater than or equal to
- `<=`: Less than or equal to

### Examples:

```swift
4 < 5        // true
0.5 > 0.1    // true
3.5 <= 3.0   // false
12 >= 15     // false
"A" == "A"   // true
"B" != "b"   // true
```

### Instructions:

#### Setup If Statement:

Create an if statement that checks if `tuneSquadPoints` is less than `monstarsPoints` using the appropriate comparison operator.
Print a message for the winning team within the body of the if statement.

```swift
if tuneSquadPoints < monstarsPoints {
    print("Monstars win!")
}
```

#### Setup Else Statement:

Add an else statement.
Print a message for the other winning team within the body of the else statement.

```swift
else {
    print("TuneSquad win!")
}
```

### Explanation:

- The if statement checks if `tuneSquadPoints` is less than `monstarsPoints`. If this condition is true, it prints "Monstars win!"
- The else statement handles the scenario where `tuneSquadPoints` is not less than `monstarsPoints`, indicating that TuneSquad wins. It prints "TuneSquad win!".

This program demonstrates the use of comparison operators to determine the winning team in a basketball game between TuneSquad and Monstars.

Twitter: [Follow me for updates!](https://twitter.com/bhushcodes) 🐦

Next: [Conditionals - Comparison Operators](3/Conditionals_And_Logic/Else_If_Statements/README.md)
