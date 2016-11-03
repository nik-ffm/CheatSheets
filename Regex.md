#RegEx


##Anchors
``` sh
^ # Start of string, or start of line in multi-line pattern
\A # Start of string
$ # End of string, or end of line in multi-line pattern
\Z # End of string
\b # Word boundary
\B # Not word boundary
\< # Start of word
\> # End of word
```

##Character Classes
``` sh
\c # Control character
\s # White space
\S # Not white space
\d # Digit
\D # Not digit
\w # Word
\W # Not word
\x # Hexade­cimal digit
\O # Octal digit
```

##Quanti­fiers
``` sh
*     # 0 or more
{3}   # Exactly 3
+     # 1 or more
{3,}  # 3 or more
?     # 0 or 1
{3,5} # 3, 4 or 5
``` 

## Examples

```sh
3[47][0-9]{13} # credit card number (15 digits and starting with 34 or 37)
\d{1,3}\.\d{1,3}\.\d{1,3}\.\d{1,3} # IP addresses like 192.168.0.1

```