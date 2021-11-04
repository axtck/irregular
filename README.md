# Irregular

***Regular Expressions***

---

### Assertions / Quantifiers 
* ``^ beginning of line
* $         end of line
* \*         0 or more
* ?         0 or 1
* +         1 or more
* {n}       exactly n
* {n,}      n or more
* {n, m}    between n and m


### Characters
.         any except newline
\.        period
[abc]     only a, b, or c
[^abc]    anything but a, b or c
[a-z]     a to z
[0-8]     0 to 8
\d        digit
\D        non-digit
\s        space
\S        non-space
\w        alphanumerical character 
\W        non-alphanumerical character


### Special
\n        newline
\t        tab


### Capturing
(...)     capture group
(a(bc))   capture sub-group
(.*)      capture all
(abc|def) matches abc or def

