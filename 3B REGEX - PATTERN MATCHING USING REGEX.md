# Exp.No:3b  
## REGEX - PATTERN MATCHING USING REGEX

---

### AIM  
To write a Python program that matches a string containing an `'a'` followed by **two to three `'b'` characters** using regular expressions.

---

### ALGORITHM

1. Begin the program.  
2. Accept a string `str1` from the user.  
3. Define the regular expression pattern as `r"[a]+b{2,3}"`.  
4. Use the `re.match()` function to check if the string `str1` matches the pattern.  
5. If a match is found, print `"Found a match!"`.  
6. If no match is found, print `"Not matched!"`.  
7. Terminate the program.

---

### PROGRAM

```
Reg No-212223060045
Name - Devesh V

import re
str=input()
pattern='^[a(b*)]+$'
x=re.search(pattern,str)
if x:
    print("Found a match!")
else:
    print("Not matched!")
```
### OUTPUT
<img width="638" height="309" alt="601361401-981cbe39-0486-47cd-8e24-fdce60723412" src="https://github.com/user-attachments/assets/28597f54-0127-4fc7-b6fa-9d33b7fde63f" />

### RESULT
Thus a Python program that matches a string that begins with "a" followed by zero or more b's has been successfully implemented.


