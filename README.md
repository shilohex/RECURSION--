# Palindrome Checker

A simple recursive function to check if a given word is a palindrome.

## Table of Contents

- [Introduction](#introduction)
- [Usage](#usage)
- [How it Works](#how-it-works)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This code contains a recursive function named `palindrome` that checks whether a given word is a palindrome or not. A palindrome is a word that reads the same backward as forward.

## Usage

To use the palindrome checker, you can call the `palindrome` function with a word as an argument. The function will return either "IT IS PALINDROME" or "IT IS NOT PALINDROME" based on whether the input word is a palindrome or not.

```pseudo
result = palindrome("level")
print(result)  // Output: IT IS PALINDROME
How it Works
The palindrome function follows a recursive approach to check for palindromes. It compares the first and last characters of the word and recursively calls itself with a substring, excluding the first and last characters, if the characters match.

Getting Started
Prerequisites
Ensure you have a platform with support for the chosen programming language where you can run the palindrome checker.

Installation
No installation is required for this code. Simply copy the palindrome function and use it in your project.

Examples
You can find examples of how to use the palindrome checker in the Examples section of this README.

Contributing
If you'd like to contribute to this project, please follow the guidelines outlined in the Contributing file.

License
This project is licensed under the MIT License - see the LICENSE.md file for details.

