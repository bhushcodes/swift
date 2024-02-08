## Switch Statement: Interval Matching

### Introduction:

The switch statement in Swift not only matches exact values but also allows for interval matching, where it checks whether a given value falls within a specific range or interval. This is particularly useful when dealing with numeric or sequential data.

### Syntax:

```swift
switch expression {
    case interval1:
        // Code to execute if expression falls within interval1
    case interval2:
        // Code to execute if expression falls within interval2
    // More cases...
    default:
        // Default code to execute if expression does not match any interval
}
```

### Instructions:

#### Create Switch Statement:

Declare a switch statement with the `episode` variable as its expression.

#### Add Case Intervals:

Inside the switch statement, create case intervals using the provided information for each Star Wars episode.
Each case interval should specify the range of episodes and assign the corresponding villain to the `villain` variable.

#### Add Default Case:

Include a default case to handle scenarios where the episode does not match any specified interval. Assign an empty string `""` to the `villain` variable in this case.

#### Print Result:

Print the value of the `villain` variable after the switch statement to see the determined villain for the given episode.

### Code Example:

```swift
var episode = 5
var villain: String

switch episode {
  case 1...3:
    villain = "Emperor Palpatine"
  case 4...6:
    villain = "Darth Vader"
  case 7...9:
    villain = "Kylo Ren"
  default:
    villain = ""
}

print(villain) // Prints: Darth Vader
```

### Explanation:

- The switch statement evaluates the value of `episode`.
- Depending on which range `episode` falls into, it assigns the corresponding villain to the `villain` variable.
- In this example, since `episode` is 5, it falls within the range 4...6, so the villain is assigned as "Darth Vader".
- The print statement then displays the determined villain.

Twitter: [Follow me for updates!](https://twitter.com/bhushcodes) 🐦

Next: [Conditionals - Switch Statement: Compound Cases](/3/Conditionals_And_Logic/Switch%20Statement:%20Compound%20Cases/README.md)
