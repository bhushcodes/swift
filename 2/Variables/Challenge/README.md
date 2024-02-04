# Challenge: Temperature Conversion

## Introduction:

In this challenge, we will write a program to convert a temperature from Fahrenheit (°F) to Celsius (°C) using a specific formula.

## Instructions:

### 1.Declare Variables:

- Search for the current temperature of New York City in Fahrenheit.
- Declare a `Double` variable named `tempf` and initialize it with the temperature.
  -Declare another `Double` variable named `tempc`.

```swift
var tempf: Double = 75.0 // Replace 75.0 with the actual temperature in Fahrenheit
var tempc: Double
```

### 2. Temperature Conversion:

- Convert the temperature to Celsius using the provided formula.
- Store the result in the variable `tempc`.

```swift
tempc = (tempf - 32) / 1.8
```

3. Display Result:

- Display the result using string interpolation.
- Output exactly like so: "The temp is [tempc] degrees Celsius."

```swift
print("The temp is \(tempc) degrees Celsius.")
```

#### Explanation:

- `var tempf: Double = 75.0`: Declares a `Double` variable named `tempf` and initializes it with the temperature in Fahrenheit (replace `75.0` with the actual temperature).
- `var tempc: Double`: Declares another `Double` variable named `tempc`.
- `tempc = (tempf - 32) / 1.8`: Converts the temperature from Fahrenheit to Celsius using the provided formula and stores the result in tempc.
- print("The temp is \(tempc) degrees Celsius."): Displays the result using string interpolation, printing "The temp is [tempc] degrees Celsius."

This program demonstrates the conversion of a temperature from Fahrenheit to Celsius and outputs the result in a human-readable format.

Twitter: [Follow me for updates!](https://twitter.com/bhushcodes) 🐦

[Cheatsheet 📄](/2/Variables/Cheatsheet/Cheatsheet.png)
