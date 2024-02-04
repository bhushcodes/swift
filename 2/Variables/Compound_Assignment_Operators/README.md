# Swift Variables and Compound Assignment Operators

## Introduction:

Compound assignment operators provide a concise way to modify the value of variables. They combine an arithmetic operation with the assignment operation. Common compound assignment operators include `+=`, `-=`, `*=`, `/=`, and `%=`.

### Instructions:

Starting Inventory:

Imagine being the owner of a small fruit stand. To start the day, there are 16 apples in the inventory.

```swift
var apples = 16
```

#### Customer Purchase - Part 1:

Suppose a customer comes in and buys 4 apples. Use a compound assignment operator (`-=`) to adjust the value of apples.

```swift
apples -= 4
// Equivalent to apples = apples - 4
```

Customer Purchase - Part 2:

Another customer purchases half of the available apples.

```swift
apples /= 2
// Equivalent to apples = apples / 2
```

### Printing Final Inventory:

```swift
print(apples)
// Prints the final value of the variable 'apples'.
```

### Explanation:

- `var apples = 16`: Initializes a variable named `apples` with an initial value of `16`.
- `apples -= 4`: Uses the compound assignment operator `-=` to subtract 4 from the current value of `apples`.
- `apples /= 2`: Uses the compound assignment operator `/=` to divide the current value of `apples` by 2.
- `print(apples)`: Outputs the final value of the variable `apples`.

By the end of this program, the variable `apples` reflects the changes made through the customer purchases. Adjustments were made using compound assignment operators for a more concise and readable code.

Twitter: [Follow me for updates!](https://twitter.com/bhushcodes) 🐦

Next: [Variables - Type](/2/Variables/Type/README.md)
