# Regex for Matching Emails

Hey there! Ever seen a string of characters used to check if something is in the right format? That's called a Regular Expression, or 'regex' for short. Today, we're going to look at one that checks if emails are written right.


## Summary

Here's our email checker:

'/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/'
This expression helps make sure emails look like "someone@example.com".


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

'^': Says "start here".
'$': Says "end here".

### Quantifiers

'+': Means "at least once". 

### Grouping Constructs

1. '([a-z0-9_\.-]+)': This checks the "someone" in "someone@example.com".
2. '([\da-z\.-]+):' This checks the "example" part.
3. '([a-z\.]{2,6})':This checks the ".com" at the end.

### Bracket Expressions

'[a-z0-9_\.-]': These are the letters and symbols we're okay with.

### Character Classes

'\d': This means any number, like 0, 1, 2, and so on.

### Character Escapes

'\.': Just means we're looking for a dot, like in ".com".

## Author
Modvision