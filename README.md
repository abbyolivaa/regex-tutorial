# regex-tutorial

# Table of Contents

1. [Regex](#Regex)


2. [Anchors](#Anchors)


3. [Quantifiers](#Quantifiers)


4. [CharacterClasses](#CharacterClasses)


5. [Flags](#Flags)


6. [Grouping&Capturing](#Grouping&Capturing)


7. [BracketExpressions](#BracketExpressions)


8. [Boundaries](#Boundaries)



## Regex
  **Regex, or regular expression, is a string of text that searches for a specific pattern in an input text**
  
  For example: /^([a-z0-9_.-]+)@([\da-z.-]+).([a-z.]{2,6})$/
  
  This regex searches for an email address that begins with characters an "@" and the domain.
  
## Anchors
**Regex Anchors Anchors belong to the family of regex tokens that don't match any characters, but that assert something about the string or the matching process**

**^** : this anchor indicates the beginning of the string,

**$** : this anchor indicates the end of the string

## Quantifiers
**In Regex, quantifiers specify how many instances of character group or character class present in the input for a match to be found.**

**+** : used to match one or more of the preceding token,

**{2,6}** : matches the specified quantity of the previous token (between 2 and 6 characters).
  - 2 digits exactly, or...

**{2,4}** : looks for 2 or more characters.


## CharacterClasses
**In regular expressions, a character class allows one to define a custom set of characters that are allowed in a match.**

**.** : any character except a line break,
  - By placing a backslash \ in front of the ., it's "escaping" the character

**\d** : matches any single digit equivalent to [0-9].

## Flags
**Regular expression patterns are often used with modifiers (also called flags) that redefine regex behavior.**

**g** : global search

## Grouping&Capturing

## BracketExpressions

## Boundaries

##Author
https://github.com/abbyoliva/abbyoliva/tree/main
  
  
