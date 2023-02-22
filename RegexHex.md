# Matching a Hex Value 

Regular expressions also known as regex are used for pattern matching. hex values are commonly used in web development. I will be explaining the different components of the regex used.    


## Summary

I be will explaining how to match a hex value using regular expressions. The regex used for this is

/^#?([a-f0-9]{6}|[a-f0-9]{3})$/

Below are details explaining the different components of this regex and how they work together to match a hex value.

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

Anchors are used to specify where a pattern should match in the text. The caret symbol (^) is used to anchor the pattern to the beginning of the text while the dollar symbol ($) is used at the end. An example of this is in this code 

/^#?([a-f0-9]{6}|[a-f0-9]{3})$/

at the beginning theres a caret and at the end theres a dollar symbol.



### Quantifiers

Quantifiers are used to specify how many times a pattern should match. the curly braces ({}) are used to specify a specific number of matches. In the code snippet provided theres a 6 and 3 which indicate the instances of the string.

### Grouping Constructs

Grouping constructs are used to group together parts of a pattern. In this case the parantheses () are used to create a group. In this example the group created is ([a-f0-9]{6}|[a-f0-9]{3}).

### Bracket Expressions

Bracket expressions are used to match a single character from a set of characters. In this example '[a-f0-9]' which the hexadecimal digit is from 0-9 or a-f.

### Character Classes

Character classes are used to match a character from a specific category of characters. 

### The OR Operator

The OR operator is used to match either one option or the other. In this example (|) is used to match either the 6 or the 3 digit value.

### Flags

Flags are used to modfy the behavior of the regex.

### Character Escapes

Character escapes are used to match a character that has a special meaning. In this example the backslash is used to escape the hashtag.

## Author

My name is Leo Segura full stack web developer. I have many projects that im currently working on and or are finished on my github profile.

[Github](https://github.com/lsegura06)