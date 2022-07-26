# Regex Tutorial 
Regular expressions are patterns used to match character combinations in strings. In JavaScript, regular expressions are also objects. 

## Summary
In this tutorial, i will be explaining how regex will be used to match hex values.  
Hexadecimal code is a system by which any specific color can be described accurately to a computer, ensuring consistency and accuracy in an electronic display. 
A hexadecimal color value is a six-digit code preceded by a # sign; it defines a color that is used in a website or a computer program. /^#?([a-f0-9]{6}|[a-f0-9]{3})$/

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)

## Regex Components

### Anchors
Anchors do ot match any character at all. Instead, they match a position before, after, or between characters. They can be used to “anchor” the regex match at a certain position. The caret ^ matches the position before the first character in the string. Applying ^a to abc matches a. ^b does not match abc at all, because the b cannot be matched right after the start of the string, matched by ^.

### Quantifiers
Quantifiers are used to communicate how many characters are expected. Quantifiers specify how many instances of a character, group, or character class must be present in the input for a match to be found. By default, quantifiers are greedy, and will match as many characters as possible.

### OR Operator
The "or" operator within a regular expression is defined using the | element. The or operator indicates that it could either of the components that we are separating with the |.

### Character Classes
Character classes are components within our regular expression that tells us what type of characters to expect. In our example our character classes are confined within brackets [].

### Bracket Expressions
Matches any character in the square brackets. 

### Greedy and Lazy Match
A greedy match tries to match an element as many times as possible. Whereas, a lazy match tries to match an element as few times as possible. In our example we have ? which signifies lazy quantifier. This is referred to a lazy quantifier because it causes the regular expression engine to match as few occurances as possible. We can simply turn this lazy match into a greedy one by adding a ?.


## Author

[Cristian Kaikai](https://github.com/ckaikai19)
