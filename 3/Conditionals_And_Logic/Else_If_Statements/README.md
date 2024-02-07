## Swift Else If Statements

### Introduction:

In Swift, the else if statement allows us to add additional conditions to a standard if/else statement. It provides a way to handle multiple possible conditions in a structured manner.

### Instructions:

#### Declare Language Abbreviations:

Use a multi-line comment at the top of the file to store the abbreviations and corresponding languages spoken in New York.

```swift
/*
Abbreviations and Languages:
- EN: English
- ES: Spanish
- CH: Chinese
- RU: Russian
*/
```

### Declare Variable:

Declare a variable named `abbreviation` and assign it one of the language abbreviations.

```swift
let abbreviation = "ES" // Example abbreviation
```

### Setup If/Else If Statements:

Create an if/else statement containing three else if statements.
Each if and else if statement should check if `abbreviation` is equal to an abbreviation stored in the comment.
Within each if and else if statement's code block, print the corresponding language.
Use an else statement after the last else if statement to print the message "Abbreviation not found."

```swift
if abbreviation == "EN" {
    print("English")
} else if abbreviation == "ES" {
    print("Spanish")
} else if abbreviation == "CH" {
    print("Chinese")
} else if abbreviation == "RU" {
    print("Russian")
} else {
    print("Abbreviation not found.")
}
```

### Explanation:

- The program uses an `if/else` statement with multiple `else if` conditions to check the value of `abbreviation` against different language abbreviations.
- If `abbreviation` matches a known abbreviation, the corresponding language is printed.
- If none of the conditions are met, indicating an unknown abbreviation, the program prints "Abbreviation not found."

This program demonstrates the use of `else if` statements to handle multiple conditions and provide appropriate responses based on the value of a variable.

Twitter: [Follow me for updates!](https://twitter.com/bhushcodes) 🐦
