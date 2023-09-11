##  Explaining Regular Expressions in JS
In this tutorial im going to give you the tools to using regular expression in javascript and how it can help you in future on your projects.
# Summary
A regular expression pattern is composed of simple characters, such as /abc/, or a combination of simple and special characters, such as /ab*c/ or /Chapter (\d+)\.\d*/. The last example includes parentheses, which are used as a memory device. The match made with this part of the pattern is remembered for later use, as described in Using groups.
# Different special characters that fit into each category
Assertions
Character Classes
Groups and Backreferences
Quantifiers
Escaping
# Quantifiers
Indicate numbers of characters or expressions to match.
# Character Classes
Distinguish different types of characters. For example, distinguishing between letters and digits.
# Groups and Backreferences
Groups group multiple patterns as a whole, and capturing groups provide extra submatch information when using a regular expression pattern to match against a string. Backreferences refer to a previously captured group in the same regular expression.
# Assertions
Assertions include boundaries, which indicate the beginnings and endings of lines and words, and other patterns indicating in some way that a match is possible (including look-ahead, look-behind, and conditional expressions).

# Escaping
If you need to use any of the special characters literally (actually searching for a "*", for instance), you must escape it by putting a backslash in front of it. For instance, to search for "a" followed by "*" followed by "b", you'd use /a\*b/ — the backslash "escapes" the "*", making it literal instead of special.
# Author
Tyson Starks-Vaught

