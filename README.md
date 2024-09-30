# Excel Shortcuts
---

## Remove the last word from the student name


```excel

=IF(LEN(A1)-LEN(SUBSTITUTE(A1," ",""))>1, LEFT(A1,FIND("☐",SUBSTITUTE(A1," ","☐",LEN(A1)-LEN(SUBSTITUTE(A1," ",""))))-1), A1)

```
