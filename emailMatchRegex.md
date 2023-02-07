# Matching an Email (Regex)

## Summary

Matching an Email: `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

A regex like this will be used to validate an email address. The numerous letters, numbers, and symbols may look confusing and intimidating, but it is more simple than you may think. Lets break it all down. The expression will start and end with a forward slash. This will be true for every regex. The first set of characters, ([a-z0-9_\.-]+) will be used to validate the beginning of an email, this will cover all letters before the @ symbol. Speaking of, the @ symbol will be next up, it will separate the beginning from the end of the email. The next portion will be the domain ".com" , ".net" , ".org" , etc... This section of the email validation will require these characters ([\da-z\.-]+)\.([a-z\.]{2,6}) most importantly being the dot within the domain. Lets now break down these sections in more detail!



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

- Caret: The ^ symbol, known as a caret denotes the start of a string. This is why it is the first symbol to appear within a regex.

- Dollar: The $ sign appears opposite of the caret, at the end of the regex. This is to match the final character of the string.

- 

### Quantifiers

- Quantifiers can appear as either a + or a * symbol let us know how many times a character can be used. The + sign means that it can be used once more, while the * means that it can be used 0 more times, thus making that character type optional.

### Grouping Constructs

- Grouping Constructs such as "Matched Subexpressions" are used to match character combinations within strings.

### Bracket Expressions 

- Bracket Expressions: [a-z0-9_\.-] indicate a given set of characters to be matched. All characters provided within the strings will be matched.

### Character Classes

- Character Classes are used to distinguish between different numbers, letters, and symbols. For example, [a-z] species the full range of the alphabet. 


### Flags

- A flag changes the search behavior of a regex. There are six total flags which we will discuss now.

- Ignore casing: The "i" makes the search case insensitive.

- Global: The "g" flag forces a search for all occurances.

- Dot All: The "s" flag makes the dot "." symbol matche new lines.

- Sticky: the "y" flag makes an expression search from the lastIndex property.

- Unicode: the "u" flag assumes an individual characters are code points.

## Author

Hey! My name is Luke, an aspiring front end developer currently studying at the University of Miami.

https://github.com/Lmickk2
