# Regex Tutorial

## Summary

This is a quick tutorial on how an email regex is used. This is the email regex /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)

## Regex Components

### Anchors

The anchors are the ^ at the start of the syntax and $ at the end of the syntax.

### Quantifiers

The quantifiers are the + and {}.
- The + Matches the pattern one or more times
- The {2,6} Matches the pattern from a minimum of 2 number of times to a maximum of 6 number of times

### Character Classes

The Character class is /d, which is equivalent to the bracket expression [0-9].

### Grouping and Capturing

Theres three groups that are captured in the email regex, ([a-z0-9_\.-]+), ([\da-z\.-]+) and ([a-z\.]{2,6}).
- ([a-z0-9_\.-]+) is saying there must be more than one character that could be from a-z, and 0-9.
- ([\da-z\.-]+) is saying it must be /d atleast a character from a-z, /, or a -
- ([a-z\.]{2,6}) is saying there must be 2-6 characters that could be a-z, or /.

### Bracket Expressions
Theres three bracket expressions, [a-z0-9_\.-], [\da-z\.-] and [a-z\.].
- [a-z0-9_\.-] is saying to add characters from a-z, numbers from 0-9, underscores, periods and dashes.
- [\da-z\.-] is saying to add all characters from a-z, periods and dashes.
- [a-z\.] is saying to add characters from a-z.

## Author

I'm a bootcamp student at the university of Toronto, you can find my git hub here [GitHub](https://github.com/sw33ws).
