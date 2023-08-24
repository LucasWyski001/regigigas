# Title Matching a Hex Value

In this tutorial were going to explain what matching a Hex Value is and how this can be useful

## Summary
This md will be describing the breakdown of the following regex function of /^#? ([a-f0-9] {6}| [a-f0-9] {3})$/ which is used to match hex values.
Cool tip Hex codes are hexidecimal codes in a format for identifying colors in specificity.


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
the anchors of the Hex Value for the regex function is the /^ starting indicator and the $/ ending indicator the code.
The anchors are essentially used to show the start and end of the expression
### Quantifiers
The quantifiers of thos regex are the ? {6} and {3} for this instance if we are looking at the code: /^#? ([a-f0-9] {6}| [a-f0-9] {3})$/ .
this essentially says how many instances of a chracter, group, orchracter class needs to be present in a input for a match to be found.
the ? is meant to match zero or one time, where the {6} and {3} wopuld essentially say which type of hex formatto use, the formats are Hex triplet and shorthand hex.

### Grouping Constructs
/^#? ([a-f0-9] {6}| [a-f0-9] {3})$/ the constructs within the hex code are ([a-f0-9] {6}| [a-f0-9] {3}).
the parenthis () are used to group the sequence, where the a-f0-9 is sayinf that the group is going to be 6 values, or 3 values of a-f0-9.

### Bracket Expressions
The bracket espression is used to match the pattern of the sequence, for example for the [a-f0-9], the expression is matching any lower case between a-f and numbers 0-9

### Character Classes
The chracter classes are essentially the guts of the code snippet here, they are in this instance a-f0-9 a-f0-9 they get the chracters range essentially so for this
instance a-f 0-9.

### The OR Operator
 /^#? ([a-f0-9] {6}| [a-f0-9] {3})$/ in this snippet of code the or operator is the | within the code, which is used to match the before or after. So
 in this expression its saying it can be either 6 characters OR 3

## Author
Lucas Wysoczanski

https://github.com/LucasWyski001


A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
