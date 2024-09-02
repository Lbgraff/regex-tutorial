# Regex Tutorial

This is an explanation for the regular expression for searching an email.

## Summary

 `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

 Above is the regular expression (or regex) for searching for an email address. I will explain the parameters of the regex below.

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

The `/^` and `$/` represent anchors, which are not characters that are searched in themselves but are used to signify the beginning and end of the search parameter.

### Quantifiers

The `{2,6}` are quantifiers, which signify how many characters must be present in order to match the expression. This example means that the characters must be of a length between 2 and 6. A matching example would be `aol`.

### Character Classes

Character classes match any character included in a list. `a-z` matches any letter between a and z. `0-9` matches any digit between 0 and 9. A matching example would be `b2`.

### Grouping and Capturing

Parentheses in the regex example above represent the capture of the group of characters between them. `([a-z0-9_\.-]+)` , `([\da-z\.-]+)` , and `([a-z\.]{2,6})` contain parentheses which separate the capture group inside of them. A matching example would be `abc123`.

### Bracket Expressions

Brackets create groups of enclosed characters. `[a-z0-9_\.-]` denotes a group of characters that will be searched together. `[a-z\.]` does the same thing. A matching example would be `abc_123`.

## Author

I am a student of the UT Full Stack Coding Boot Camp. I am learning how to code so that I can become a software developer. I am very excited to utiliize my new skills as I go forth into the professional programming world. See my Github profile for my portfolio of projects I have completed as a boot camp student.

Link to Github profile: https://github.com/Lbgraff
