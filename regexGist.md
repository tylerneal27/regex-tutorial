# William/'s regex tutorial

This tutorial will break down different components of an email regex. 

## Summary

The following regex is designed to collect a valid email:

`/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

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

This regex has two Anchors a beginning(^) and an end($). 

### Quantifiers

The first two character sets have plus(+) Quantifiers to match one or more of the preceding tokens and for the third character set it has {2,6} Quantifiers to match between 2-6 of the preceding tokens.

### OR Operator

This regex has none.

### Character Classes

the first character set takes in two ranges from a-z and 0-9 also allows these characters ( -, _, . ). The second character set takes in a digit 0-9 but show as \d then a range of a-z with (-, .)

### Flags

### Grouping and Capturing

This regex has 3 capturing groups first take in your email second takes in email provider and the third takes in the domain extension.

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)