# Python Regular Expression

a sequence of characters used to check whether a pattern exists in a given text (string) or not
Regular Expression used at the server side to validate the format of email addresses or passwords during registration, used for parsing text data files to find, replace, or delete certain string

In Python, regular expressions are supported by the re module to import this module write :
`import re`
There is no need to add the module to poetry

basic patterns in Python using ordinary characters . They match themselves exactly , example :

```pattern = r"Cookie“
sequence = "Cookie"
re.match(pattern, sequence)
```

he **match()** function returns a match object if the text matches the pattern. Otherwise, it returns None

the r at the start of the pattern is called a raw string literal. It changes how the string literal is interpreted. Such literals are stored as they appear


**^ - A caret**. Matches the start of the string.
It is used to check that a document/sentence starts with certain characters.
Example :
`re.search(r'^Eat', "Eat cake!").group()`

$ - Matches the end of string.
It is used to check that a document/sentence ends with certain characters.
Example :
` re.search(r'cake$', "Cake! Let's eat cake").group() `

[] used to matches any Characters that are within a range (a to z) or (A to Z) or (0 to 9) :
Example :
` re.search(r'[0-6]', 'Number: 5 2 4').group()`
It matches just the first Characters within the range : (5)

[^(the range)] :
If the first character of the set is ^, all the characters that are not in the set will be matched .
Example : 
` re.search(r'[^0-5]', '543791').group()`
The output will be 7 because it is the first character from out of the range 

**\ - Backslash :**
- \w - Lowercase 'w'. Matches any single letter, digit, or underscore.
- \W - Uppercase 'W'. Matches any character not part of \w (lowercase w).
- \s - Lowercase 's'. Matches a single whitespace character like: space, newline, tab, return.
- \S - Uppercase 'S'. Matches any character not part of \s (lowercase s).
- \d - Lowercase d. Matches decimal digit 0-9.
- \D - Uppercase d. Matches any character that is not a decimal digit.


Repetitions :
+ - Checks if the preceding character appears one or more times starting from that position.
* - Checks if the preceding character appears zero or more times starting from that position
? - Checks if the preceding character appears exactly zero or one time starting from that position.


to use an expression several times in a single program, using compile() to save the resulting regular expression object
The match() function checks for a match only at the beginning of the string (by default), whereas the search() function checks for a match anywhere in the string.
