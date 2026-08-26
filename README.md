# String Library

A C++ string manipulation library that provides a collection of reusable functions for analyzing, formatting, transforming, and processing strings.

The library supports various string operations, including word counting, letter case conversion, string splitting and joining, trimming, word replacement, reversing words, vowel counting, and punctuation removal.

## Features

- Create and manage string objects.
- Get and set string values.
- Calculate string length.
- Count words in a string.
- Convert the first letter of each word to uppercase or lowercase.
- Convert the entire string to uppercase or lowercase.
- Invert the case of all letters.
- Count capital and small letters.
- Count specific letters with optional case matching.
- Check whether a character is a vowel.
- Count vowels in a string.
- Split strings using a custom delimiter.
- Trim spaces from the left, right, or both sides.
- Join strings from a vector or array.
- Reverse the order of words in a string.
- Replace specific words with optional case-sensitive matching.
- Remove punctuation characters from a string.
- Support both static functions and object-based methods.

## Technologies Used

- C++
- Standard Library
- Object-Oriented Programming (OOP)
- Classes
- Static Methods
- Vectors (`vector`)
- String Manipulation
- Character Handling

## Getting Started

### Prerequisites

To use this library, you need:

- A C++ compiler such as GCC or Microsoft Visual C++.
- A C++ development environment such as Visual Studio or Visual Studio Code.

### How to Run

1. Clone the repository:

`git clone https://github.com/Omar-Dev-05/String-Library.git`

2. Open the project in your preferred C++ IDE.

3. Make sure `ClsString.h` is included in the project.

4. Build the project.

5. Run `main.cpp` to test the library and its available string operations.

## Usage

The library provides multiple ways to create and manipulate strings.

### Creating a String Object

`clsString String1;`

### Creating a String with an Initial Value

`clsString String2("Mohammed");`

### Setting a String Value

`String1.Value = "Ali Ahmed";`

### Counting Words

`String1.CountWords();`

### Changing Letter Case

`String3.UpperAllString();`

`String3.LowerAllString();`

### Splitting a String

`vector<string> vString = String3.Split(" ");`

### Removing Extra Spaces

`String3.Trim();`

### Reversing Words

`String3.ReverseWordsInString();`

### Replacing a Word

`String3.ReplaceWord("Mohammed", "Sari");`

### Removing Punctuation

`String3.RemovePunctuations();`

## Project Structure

- `ClsString.h` — Contains the `clsString` class and string manipulation functionality.
- `main.cpp` — Demonstrates and tests the different string operations provided by the library.

## About the Author

**Omar Abobakr** is a software developer focused on problem-solving and building practical software projects.
