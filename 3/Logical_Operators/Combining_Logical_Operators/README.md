# Combining Logical Operators in swift

Combining logical operators in Swift allows us to create more complex conditions by chaining multiple conditions together. We primarily use the && (logical AND) and || (logical OR) operators to combine conditions, and sometimes we use the ! (logical NOT) operator to negate a condition.

Let's understand this with an example:

```swift
let weekday = true
let dayOff = false
let weekend = false

if weekday && dayOff || weekend {
  print("Do something fun!")
} else {
  print("Get some work done")
}
// Prints: Get some work done
```

In this example, we have three boolean variables: `weekday`, `dayOff`, and `weekend`. The if statement checks the following condition:

1. `weekday && dayOff`: This condition evaluates to false because `weekday` is true and `dayOff` is false (using the && operator). So, this part of the expression becomes false.
2. `false || weekend`: Since the first part of the condition is false, the condition `false || weekend` is evaluated next (using the || operator). Here, `weekend` is also false. The || operator returns true if at least one of the conditions is true, but since both are false, the overall result of this expression is false.

So, the second code block (the else block) gets executed, and it prints "Get some work done".

Now, let's apply this concept to the given instructions:

1. In `Security.swift`, there are three variables representing different conditions for unlocking an iPhone: `correctPassword`, `lessThanThreeTries`, and `accessThroughTouchID`.

2. We need to create an if statement with the following logic:

   - If a user enters the correct password AND had less than three tries OR has access through TouchID, then set `unlock` to true.

3. Add an else statement to handle the case where the conditions are not met, and within its body, reassign `unlock` to false.

4. Finally, print the value of `unlock`.

Here's how the Swift code looks like:

```swift
let correctPassword = true
let lessThanThreeTries = false
let accessThroughTouchID = true
var unlock = false

if correctPassword && lessThanThreeTries || accessThroughTouchID {
    unlock = true
} else {
    unlock = false
}

print(unlock)
```

You can test this code with different combinations of boolean values for `correctPassword`, `lessThanThreeTries`, and `accessThroughTouchID` to observe how the unlocking condition changes based on different scenarios.

Twitter: [Follow me for updates!](https://twitter.com/bhushcodes) 🐦

Next: [Conditionals - Logical Operators - Controlling Order of Execution](/3/Logical_Operators/Controlling_Order_Of_Execution/README.md)
