# Regex Tutorial

In this tutorial, users will learn how a specific regular expression, or regex, functions by breaking down each part of the expression and what it does by matching an email.

## Summary

A regular expression(regex), can be defined as sequence of characters defining a specific search pattern. It is also used for string matching. Regex is also commonly used to validate input. For this tutorial we will be matching an email -` /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/. `

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components

### Anchors
To anchor an email used in this regex expression you'll need to start with `^` in front of the string, and end the string with `$`.
### Quantifiers
Some quantifiers(specifiers of how many instances of a character, group, or character class must be present in the input for a match to be found.) for matching an email in this instance are `+`(matching 0 or 1 of the previous) and `{2, 6}`(matching everything between 2-6).
### OR Operator

### Character Classes
The character class shown in this regex is `/d`. This class takes one degit and matches it.

### Grouping and Capturing
There is also grouping in this regex. `[0-9]` and `[a-z]` match digits and characters in specified ranges.


### Greedy and Lazy Match
The regular expression above is by default greedy(tries to extract as much as possible until it conforms to a pattern even when a smaller part would have been syntactically sufficient). With the `+` quantifier, , it will match as many times as possible.


## Author

Contact Information:
-Email: [deaijaemungin@gmail.com] -GitHub: [https://github.com/OZ4Tech]
