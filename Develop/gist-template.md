# Regex you never knew

Simple Regex Tutorial

## Summary

Matching a Hex Value – /^#?([a-f0-9]{6}|[a-f0-9]{3})$/

## Table of Contents

- [^](#anchors)
- [a-f0-9](#quantifiers)
- [[]](#or-operator)
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

^ this is an anchor. This component is used to match the exact start of our search word. For example, in this case ^ is preceeded with the # and only. So, we will match:

```
#234
#Banana
#Whatever
```

But not:

```
234#
234
2#34
```

### a-f0-9

a-f This means that we would like to have any lowercase letter between a and f included:

```
a b c d e f
```

0-9 means that we expect any number beetween 0 and 9.

```
0 1 2 3 4 5 6 7 8 9
```

### []

Everything that goes inside the square brackets can be written in any order.

For instance, [0-9] will match:

```
1
2
3
4...
```

{3}

### Character Classes

### Flags

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)