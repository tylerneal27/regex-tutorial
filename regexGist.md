# William/'s regex tutorial

This tutorial will break down different components of an email regex. 

## Summary

The following regex is designed to collect a valid email:

`/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

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

This regex has two Anchors a beginning`(^)` and an end`($)`.

### Quantifiers

The first two character sets have plus`(+)` Quantifiers to match one or more of the preceding tokens and for the third character set it has `{2,6}` Quantifiers to match between 2-6 of the preceding tokens.

### Grouping Constructs

This regex has 3 capturing groups first take in your email`([a-z0-9_\.-]+)` second takes in email provider`([\da-z\.-]+)` and the third takes in the domain extension`[a-z\.]`.

### Bracket Expressions

the first bracket takes in two ranges from `a-z` and `0-9` also matches these characters `( -, _, . )`. The second bracket takes in a range of `a-z` with `(-, .)` characters available. The third bracket taking a range of `a-z` and an escaped character of `(.)`.

### Character Classes

a digit 0-9 but show as `\d` in the regex also only takes in a single digit.

### The OR Operator

This regex has none but is normally a `(|)` symbol.

### Flags

this regex has zero flags but some common ones are ignore case`(i)`, global search`(g)`, multiline`(m)`, unicode`(u)`, sticky`(y)`, dotall`(s)`.


## Author: William Neal

hope this helps with learning regex(https://github.com/tylerneal27/regex-tutorial)