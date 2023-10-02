# Title (replace with your title)

In this beginner-friendly tutorial, we're going to unravel the secrets of regular expressions (regex). We'll use a specific regex pattern to match Social Security Numbers (SSNs) and break it down.

## Summary

In this tutorial, we'll focus on a simple regex pattern:

/^\d{3}-\d{2}-\d{4}$/

This regex is designed to match SSNs in the format XXX-XX-XXXX, where X represents digits. We'll go step by step, explaining each part of this regex and how it works.

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

Think of anchors as the beginning and end points for our match. The ^ at the start and $ at the end of our regex say, "Start matching from the beginning, and stop at the end."

### Quantifiers

Quantifiers tell us how many times something should appear. In our regex, \d{3} means "match exactly three digits." \d{2} means "match exactly two digits," and \d{4} means "match exactly four digits."

### Grouping Constructs

Groups are like containers for patterns. The parentheses () in our regex group digits together. They help us apply quantifiers to a specific part of the regex.

### Bracket Expressions

Bracket expressions allow us to specify a range of characters to match. [0-9] means "match any digit from 0 to 9." So, \d is just a shortcut for [0-9].

### Character Classes

Character classes are shortcuts for common groups of characters. \d is a shorthand for "any digit." It's more concise than [0-9].

### The OR Operator

The | symbol lets us choose between alternatives. For example, cat|dog matches either "cat" or "dog." Although not in our SSN regex, it's handy to know.

### Flags

Flags are like modifiers that change how the regex behaves. Common flags include g (global, to find all matches), i (case-insensitive), and m (multiline). We'll touch on these briefly.

### Character Escapes

Sometimes we want to match characters with special meanings, like . or \*. We use the backslash \ to escape them. For example, to match a literal dot, use \..

## Author

Thank you reading  
By: Victoria Andrade
Github: https://github.com/Vixtoriandrade
