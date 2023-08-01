## Regex Tutorial
A REGEX is a regular expression that searches for matching values/patterns within a string. Using REGEX, the following string is compared to an email address to see if it matches.

## Summary
During this regex tutorial, we will learn how to match an email address with a regex. Each component is responsible for ensuring the user enters the email address correctly, which in this case begins with characters followed by the @ symbol and finally the domain.
## Table of Contents
*Anchors
*Quantifiers
*Character Classes
*Flags
*Grouping and Capturing
*Bracket Expressions
*Greedy and Lazy Match
*Boundaries
*Back-references
*Look-ahead and Look-behind
*Questions
## Regex Components
## Anchors
As shown in the example, the Regex ^ anchor indicates the beginning of the string. Strings end with the dollar $ anchor. In our given regex
## Quantifiers
The REGEX in this example includes these following quantifiers: The + is used to match one or more of the preceding token {2,6} in this case matches the specified quantity of the previous token, for this case between 2 and 6 characters. {2,6} would be alternatives, which looks for exactly 2 digits, or {2,4} which will look for characters 2 or more.
## Character Classes
Character Classes types are distinguishedfrom a certain set. There are two character classes in our regex:. and d. Any character, excluding a line break, is represented by the. When the. is preceded by a backslash (/), it is interpreted as literally "escaping" the character. Any single digit that is [0-9] equivalent matches the d.

An illustration of \.: in the expression a\.c, it matches a.c. The . is intepreted literally - as period.
## Flags
The following flags are included in the example REGEX: G, short for "global search,"
## grouping and capturing
The group included in the example is ([a-z0-9_.-]+), which indicates that at least one or more of the letters in the square brackets [a-z0-9_.-] must match. Lowercase letters from a to z are represented by the letters a to z, 0 to 9 by digits, _ by an underscore,. by a period, and - by a hyphen.
## Bracket Expressions
Expressions with square brackets, known as brackets, are used to identify characters to match. Three bracket expressions make up our regex:  ([a-z0-9_\.-]+), ([\da-z\.-]+), and ([a-z\.]{2,6}).

A bracket expression example is [abc], which matches any character between the brackets—either a, b, or c.

## Greedy and Lazy Match
There are no greedy or lazy matches in the provided code for email matching.

## Author 
Vist my github link: https://github.com/Dennmed22/regex-tutorial