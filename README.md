# RegEx-cheatsheet
Regular Expression cheatsheet

-  \+ Match one or more character sequentially
```
/e+/i = th[eeeeeee]y // must need to have at least 1 occurance
/e+/ig = th[eeeeeee]piy[e] // single e also selected
```
-  \* Match zero or more character sequentially
```
/e*/i = th[e]y
/he*/i = t[h]y // e is optional here only h selected
/e*/ig = th[e]piy[ee]
```
- ? Match zero or one character sequentially (optional)
```
/e+y?/i = th[eeeeeeey]yyy //all e and single y
/e+y?/ig = th[eee]piy[eey]yyyy //all e ignoring the y
```

