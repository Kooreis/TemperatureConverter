# Python Documentation

# Temperature Converter

This Python script is a simple temperature converter that allows the user to convert temperatures between Celsius and Fahrenheit.

## Description

The script presents the user with two options:

1. Convert from Celsius to Fahrenheit
2. Convert from Fahrenheit to Celsius

The user is then prompted to enter their choice, followed by the temperature they wish to convert. The script then performs the appropriate conversion and prints the result.

## Usage

To use this script, simply run it in a Python environment. You will be prompted to make a choice and enter a temperature. The script will then print the converted temperature.

## Code Explanation

The script does not import any libraries, as all functionality is provided by Python's built-in functions.

The script defines a single function, `temperature_converter()`, which performs all of the script's functionality. This function first prints the available options to the user, then uses the `input()` function to get the user's choice.

If the user chooses option 1, the script prompts the user to enter a temperature in Celsius, then converts that temperature to Fahrenheit using the formula `fahrenheit = (celsius * 9/5) + 32`.

If the user chooses option 2, the script prompts the user to enter a temperature in Fahrenheit, then converts that temperature to Celsius using the formula `celsius = (fahrenheit - 32) * 5/9`.

If the user enters anything other than 1 or 2, the script prints "Invalid choice" and ends.

Finally, the script calls the `temperature_converter()` function to start the program.

---

# C# Documentation

# Temperature Converter in C#

This repository contains a simple C# script that converts temperatures between Celsius and Fahrenheit.

## Script Description

The script presents a console-based user interface that allows the user to choose between converting a temperature from Celsius to Fahrenheit or from Fahrenheit to Celsius. The user is then prompted to input the temperature to be converted, and the script outputs the converted temperature.

## Code Breakdown

The script is written in C# and uses the `System` namespace, which provides fundamental classes to base your applications upon.

Here is a brief explanation of the key components of the script:

- `using System;`: This line imports the `System` namespace, which contains fundamental classes and base types that define commonly-used value and reference data types, events and event handlers, interfaces, attributes, and processing exceptions.

- `class Program`: This line defines a new class named `Program`. In C#, every line of code that runs needs to be inside a class. In this case, `Program` is the class that contains our script.

- `static void Main(string[] args)`: This is the Main method, which is the entry point for any C# application. When the application is started, the Main method is the first method that is invoked.

- `Console.WriteLine()`: This method is used to output text to the console.

- `Console.ReadLine()`: This method is used to read the next line of characters from the standard input stream.

- `Convert.ToInt32()` and `Convert.ToDouble()`: These methods are used to convert a string input to an integer and a double respectively.

- `if` and `else if` statements: These are used to perform different actions based on different conditions. In this script, they are used to determine which conversion to perform based on the user's input.

## Usage

To use this script, you need to have a C# compiler installed on your machine. You can then compile and run the script using the command line.

---

# Java Documentation

# Temperature Converter in Java

This repository contains a simple Java script that converts temperatures between Celsius and Fahrenheit.

## Script Description

The script `TemperatureConverter.java` is a simple Java program that prompts the user to input a temperature in Celsius, converts it to Fahrenheit, and then prints the result. It then prompts the user to input a temperature in Fahrenheit, converts it to Celsius, and prints the result.

## Imported Libraries

The script imports the following Java library:

- `java.util.Scanner`: This library is part of Java's utility package. It provides a simple text scanner which can parse primitive types and strings using regular expressions. In this script, it is used to read the user's input from the console.

## Code Explanation

The script begins by creating a new `Scanner` object that reads from the console. It then prompts the user to enter a temperature in Celsius. The entered value is read using the `nextDouble()` method of the `Scanner` object, which parses the next token of the input as a `double`. This value is then converted to Fahrenheit using the formula `(celsius * 9 / 5) + 32` and the result is printed to the console.

The script then prompts the user to enter a temperature in Fahrenheit. The entered value is read in the same way as before, and is converted to Celsius using the formula `(fahrenheit - 32) * 5 / 9`. The result is then printed to the console.

## Usage

To use this script, simply run it in a Java environment. When prompted, enter the temperature to be converted and press enter. The converted temperature will be printed to the console.

---
