# Escape Sequences in Strings

Quotes are not the only characters that can be escaped inside a string.
Here is a table of common `escape` sequences:

| Code | Output|
-------|--------
\'  | single quote
\"	| double quote
\\	| backslash
\n	| new line
\r	| carriage return
\t	| tab
\b	| backspace
\f	| form feed

*Note that the backslash itself must be escaped in order
to display as a backslash.*

## Instructions
- Assign the following three lines of text into the single variable myStr using escape sequences.

FirstLine  
&emsp;&emsp;\SecondLine  
ThirdLine

You will need to use escape sequences to insert special
characters correctly. You will also need to follow the spacing
as it looks above with no additional spaces between each escape sequence.

'Note: The indentation for SecondLine is achieved with the tab escape character, not spaces.'


### Before

```javascript
const myStr = ""; // Change this line
```

### Answers

```javascript
const myStr = "FirstLine\n\t\\SecondLine\nThirdLine"
```
