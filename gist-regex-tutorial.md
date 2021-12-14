# REGEX TUTORIAL

This Regex Tutorial explains how using expression to match emails.
/^([a-z0-9_.-]+)@([\da-z.-]+).([a-z.]{2,6})$/

## Summary
```
Regex are a series of special characters that define a search pattern. A sequence of characters that defines a search pattern in a body of text A metacharacter is a character that has a special meaning during pattern processing. You use metacharacters in regular expressions to define the search criteria and any text manipulations.
-www.github.com
\d --> any digit from 0-9 
.* --> matches anything in the universe
.  --> any character
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

## Regex Components
```
Single characters
Wild card
Bracket Expressions
Control Characters
Escape character sets
Anchors
Recursive expansion
```
## Anchors
```
Special sequences which match an empty substring:
^ --> matches at the beginning of the target string
$ --> matches at the end of the target string
(m), or multiline is not enabled, so the regex will end at $
```
## Quantifiers
```
Regular expressions use quantifiers to generate unbounded matching possibilities and other matching amount specifications
* --> 0 or more occurrences of the atom
+ --> 1 or more occurrences of the atom
? --> 0 or 1 occurrences of the atom
Quantifiers in this regex:
+ --> connect the users email name + email service + .com
{2,6} --> allow a match range of 2-6 characters for the character set of [a-z\.]
```
## Grouping Constructs
```
([a-z0-9_\.-]+) --> matches the user email name
([\da-z\.-]+) --> matches the email service
([a-z\.]{2,6}) --> captures the .com
```
## Bracket Expressions
```
Represents a character set via a list of characters enclosed by the square brackets:
"[" and "]". It matches the target with any single character from the list.
Bracket expressions in thie regex:
[a-z0-9_\.-]
--> matching any letter a-z and is case senstive.
It also matches a character 0-9 and matches the characters "_" , "-" , and "."; 
[\da-z\.-]
--> matching a single digit from 0-9, any character a-z (case senstive),and the characters "." and "-".; 
[a-z\.]
--> matches any character a-z(case senstive) and the character ".".
```
## Character Classes
```
\d --> matches a single characters that is a digit from 0-9
```
## The OR Operator
```
Using the OR operator (|), the expression [abc] could be written as (a|b|c). Using our example in the grouping constructs section, we can take the original expression:

(abc):(xyz)
And then use the OR operator to convert it to the following:

(a|b|c):(x|y|z)

But in this Regex Tutorial we not using OR Operator
```
## Flags

## Character Escapes

## Author

Find more my works at Github: 
[Thai Hoang(Adam), Pham](https://github.com/ThiHoangPham)
</br>
Get in contact via email: thaihoangpham2008@gmail.com