# Regex Tutorial

Regular Expressions is a sequence of characters that specifies a search pattern in any given text. This tutorial was created to explain how a specific regular expression functions by breaking down each part.
## Matching an Email

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/


This tutorial on regex will cover how to match an email address. In order to achieve this, each individual component of the regex has a distinct responsibility to validate that the user inputs the email address in the accurate format. Specifically, this entails starting with characters, then adding an "@" symbol, and finally including the domain.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Components

### Anchors

The usage of the "^" anchor as an example of a Regex denotes the start of the string, whereas the "$" anchor denotes the end of the string. This is relevant to our specific regex.
### Quantifiers

The REGEX expression incorporates various quantifiers, including the "+" quantifier, which is designed to identify one or more instances of the preceding token. In addition, the "{2,6}" quantifier is implemented to match a specific quantity of the preceding token, in this instance between 2 and 6 characters.
### Grouping Constructs

The example features a group denoted by "([a-z0-9_\.-]+)", which contains the "+" quantifier, indicating that it matches one or more instances of any character within the square brackets "[a-z0-9_\.-]". Specifically, "a-z" refers to lowercase letters from a to z, "0-9" denotes numbers from 0 to 9, "_" represents an underscore, "\" represents back-slash, "." signifies a period, and "-" indicates a hyphen.
### Bracket Expressions

The use of square brackets [] within a regex pattern is intended to facilitate the identification of the portions of the expression that can potentially contain any or all of the characters specified within the corresponding Bracket Expression.
### Character Classes

The character classes \d is frequently utilized in regex to indicate a match for any single character that is a digit 
### The OR Operator

### Flags

### Character Escapes

## Author
David Lee - https://github.com/kpxcrew
