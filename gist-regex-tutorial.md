# REGEX TUTORIAL

This Regex Tutorial explains how using expression to match emails.
/^([a-z0-9_.-]+)@([\da-z.-]+).([a-z.]{2,6})$/

# Summary
```
Regex are a series of special characters that define a search pattern. A sequence of characters that defines a search pattern in a body of text A metacharacter is a character that has a special meaning during pattern processing. You use metacharacters in regular expressions to define the search criteria and any text manipulations.
-www.github.com \d
--> any digit from 0-9 .* 
--> matches anything in the universe . 
--> any character
```
## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

# Regex Components

## Anchors
```
Special sequences which match an empty substring:
^ --> matches at the beginning of the target string
$ --> matches at the end of the target string
(m), or multiline is not enabled, so the regex will end at $
```
## Quantifiers
```
Regular expressions use quantifiers to generate unbounded matching possibilities and other matching amount specifications.
* --> 0 or more occurrences of the atom
+ --> 1 or more occurrences of the atom
? --> 0 or 1 occurrences of the atom
Quantifiers in this regex:
+ --> connect the users email name + email service + .com. 
{2,6} --> allow a match range of 2-6 characters for the character set of [a-z\.]
```
## Grouping Constructs

## Bracket Expressions

## Character Classes

## The OR Operator

## Flags

## Character Escapes

## Author

Find more my works at Github: 
[Thai Hoang(Adam), Pham](https://github.com/ThiHoangPham)
</br>
Get in contact via email: thaihoangpham2008@gmail.com