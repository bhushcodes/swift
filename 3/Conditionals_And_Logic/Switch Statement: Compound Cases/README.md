## Switch Statement: Compound Cases

### Introduction:

Compound cases in a switch statement allow for matching multiple values to a single case. This is useful when you want to execute the same code block for several different values of the expression.

### Syntax:

```swift
switch expression {
    case value1, value2, value3:
        // Code to execute if expression matches value1, value2, or value3
    // More cases...
    default:
        // Default code to execute if expression does not match any case
}
```

Instructions:

1. **Create Switch Statement:**
   - Declare a switch statement with `planet` as its expression.
2. **Add Case Statements:**
   - Inside the switch statement, create cases for categorizing planets as either terrestrial or jovian.
   - Use compound cases to group planets belonging to the same category.
   - Print the category of each planet in its corresponding case.
3. **Handle Default Case:**
   - Add a default case to handle scenarios where the planet is not recognized.
   - Print "Unknown planet" in the default case.

Code Example:

```swift
var planet = "Earth"

switch planet {
  case "Earth", "Mercury", "Venus", "Mars":
    print("\(planet) is a Terrestrial planet.")
  case "Saturn", "Jupiter", "Uranus", "Neptune":
    print("\(planet) is a Jovian planet.")
  default:
    print("Unknown planet")
}
```

Explanation:

- The switch statement evaluates the value of `planet`.
- Compound cases group planets belonging to the same category.
- If the value of `planet` matches any of the planets listed in a compound case, the corresponding message is printed.
- If `planet` does not match any case, the default case handles it by printing "Unknown planet".

You can test this code by changing the value of `planet` to different planet names and observing the output.

Twitter: [Follow me for updates!](https://twitter.com/bhushcodes) 🐦

Next: [Conditionals - Switch Statement: Compound Cases](/3/Conditionals_And_Logic/Switch%20Statement:%20where%20Clause/README.md)
