1. What are regular expressions in Python?
Regular expressions are a powerful tool for matching patterns in strings. In Python, regular expressions are handled by the re module. The re module provides a set of functions that allow you to search for patterns in strings, replace those patterns with other strings, and split strings into a list of substrings.

2. How would you check if a string contains only numbers using a regular expression?
You could use the regular expression ^[0-9]+$ which would check to see if the string only contains numbers and is at least one character long.

3. Can you explain the difference between + and * operators?
The + operator matches one or more occurrences of the character or group that it precedes, while the * operator matches zero or more occurrences of the character or group that it precedes. So, for example, if you have the regular expression “a+b*c”, it will match any string that starts with an “a” and then has any number of b’s (including zero) before ending with a “c”.
