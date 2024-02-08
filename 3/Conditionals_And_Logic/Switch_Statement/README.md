## Swift Switch Statement

### Introduction:

In Swift, the switch statement provides a more elegant and efficient way to handle multiple conditions compared to a series of if/else if statements. It evaluates a given expression against multiple cases and executes the corresponding code block based on the matching case.

### Instructions:

#### Rewrite Conditional in Switch Statement Format:

Rewrite the existing if/else if statements in switch statement format.

#### Print Superhero Name:

After the switch statement, print the variable `superheroName`.

### Code Example:

```swift
var secretIdentity = "Bruce Wayne"
var superheroName: String

// Original else if statements
if secretIdentity == "Clark Kent" {
    superheroName = "Superman"
} else if secretIdentity == "Bruce Wayne" {
    superheroName = "Batman"
} else if secretIdentity == "Diana Prince" {
    superheroName = "Wonder Woman"
} else {
    superheroName = "Unknown"
}
print(superheroName)

// Switch statement format
switch secretIdentity {
    case "Clark Kent":
        superheroName = "Superman"
    case "Bruce Wayne":
        superheroName = "Batman"
    case "Diana Prince":
        superheroName = "Wonder Woman"
    default:
        superheroName = "Unknown"
}
print(superheroName)
```

### Explanation:

- The program initially checks the value of the `secretIdentity` variable using a series of `if/else if` statements and assigns the corresponding `superheroName`.
- Then, the program rewrites the same logic using a switch statement. Each case in the switch statement corresponds to a possible value of `secretIdentity`, and the associated code block assigns the appropriate `superheroName`.
- After the switch statement, the program prints the `superheroName` variable to verify the result.

Twitter: [Follow me for updates!](https://twitter.com/bhushcodes) 🐦

Next: [Conditionals - Switch Statement: Interval Matching](/3/Conditionals_And_Logic/Switch%20Statement:%20Interval%20Matching/README.md)
