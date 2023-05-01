# Regex Tutorial - Email Address Validation

This tutorial aims to break down and explain the functionality of a specific regular expression (regex) used for validating email addresses. When understanding this regex, you can use it to make sure the emails people enter into your web forms or anywhere else are valid. This will help you collect accurate and trustworthy data.

## Summary

The regex we'll be examining in this tutorial is used for validating email addresses:

    `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

This regular expression (regex) verifies if a user's input matches the standard format of an email address. It confirms that the email address starts with a series of characters, then an "@" symbol, followed by a domain and a top-level domain.

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

Anchors match a position before, after, or between characters. In our email regex, ^ checks for the start of the line, and $ checks for the line end.

### Quantifiers

Quantifiers decide how many characters to match. Our email regex uses the plus sign + as a quantifier. It matches one or more occurrences of the previous element. For example, [a-z0-9_.-]+ in our regex looks for one or more characters that can be a lowercase letter, a number, an underscore, a dot, or a hyphen.

### OR Operator

Our email regex does not use the OR operator, but it's usually symbolized by the pipe symbol |. The OR operator allows matching either the pattern before or after it.

### Character Classes

Our email regex includes the character class \d, which matches any number. Other common character classes include \w that matches any alphanumeric character or underscore, and \s that matches any whitespace character.

### Flags

Our email regex does not use any flags. Flags regulate the behavior of the regex. For example, the i flag is for case-insensitive matching, where uppercase and lowercase letters are treated the same.

### Grouping and Capturing

Parentheses () are used for grouping and capturing in the email regex. Each part of the email, like the username, domain, and top-level domain, is enclosed in parentheses. This lets the regex engine capture and save the matched characters for later use.

### Bracket Expressions

Bracket expressions [] are used to match any single character enclosed in them in the email regex. For example, [a-z0-9_.-] in our regex can match any lowercase letter, number, underscore, dot, or hyphen in any order.

### Greedy and Lazy Match

Our email regex does not clearly state whether to use greedy or lazy matching. However, by default, quantifiers in regex tend to be greedy, meaning they match as many characters as possible.

### Boundaries

The email regex we are discussing does not use any boundaries. Boundaries specify the position of the pattern in relation to a word.

### Back-references

The email regex we are discussing does not use back-references. However, back-references let you reuse a part of the regex match. You can refer to them using \number, where the number signifies the order of the matched group.

### Look-ahead and Look-behind

The email regex we are discussing doesn't use any look-ahead or look-behind assertions. These assertions are used to match something either preceded by (look-behind) or followed by (look-ahead) a specific pattern.

## Author

My name is Edgar T., and I'm an aspiring software engineer. I'm currently working on a project for a coding course where I'm learning how to effectively express new topics through writing during this week's topic.

Github Profile Link: https://github.com/etapm

This tutorial should provide you with a deeper understanding of the components of regular expressions using an email validation regex as an example. Thank you for reading!
