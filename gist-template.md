# Matching a Hex Value

Introductory paragraph: 

In this project I will be sharing the result of my research on breaking down the components of the following regular expression `/^#?([a-f0-9]{6}|[a-f0-9]{3})$/` 

## Summary

The purpose of the above RegEx is to match a hexadecimal value within our text editor. This expression starts and ends with a pair of forward slashes (/) since they are considered literals. followed by the staring forward slash at the beginning of the literal there is an anchor character (^) signifying that the string begins with the set of characters that follow the "^" sign. After that we see a "#" sign performing as a delimiter followed by a "?" sign enforcing to match patterns Zero or one time only. Then we are trying to group our set of strings together by using the set of "()" inside the "()" we are defining ranges of characters between letter 'a' to 'f' and numbers 0 to 9 that must match the pattern exactly 6 times or ranges of characters between 'a' to 'f' and numbers 0 to 9 that must match the pattern 3 times and at the end we bring in another anchor character "$" which signifies the end of the string with the characters preceding it.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [The OR Operator](#the-or-operator)


## Regex Components.



### Anchors

The two anchors we used in the above RegEx are "^" and "$". 

"^" --> Signifies a string that begins with the characters that follow it.

"$" --> Signifies a string that ends with the characters that precede it.


### Quantifiers

The two quantifires that were used in the "Matching a Hex Value" RegEx were "{6}", "{3}" and "?".

"{}" --> it enforces to match only the number of time that is defined in tha curly brackets.

"?" --> It matches the pattern zero or one time only.


### Grouping Constructs

We used a pair of "()" in the regEx literal.

"()" --> is used for grouping and in this case we are grouping two different constraints to choose from.


### Bracket Expressions

"[]" has been used twice in the above RegEx.

"[]" --> mainly used to define ranges of characters. They are alson known as "the positive character group".


### The OR Operator

We used the OR Operator once in the RegEx literal.

"|" --> unlike "[]" where you could choose a character, with "|" you must choose one of the two or more that are seperated by "|" operator.


## Author

Rodd Azad

Github Username: roddazad
