# Solution
```
def swap_case(s):
    newstr=''
    for x in range(len(s)):
        if(s[x].islower()):
            newstr=newstr+s[x].upper()
        elif(s[x].isupper()):
            newstr=newstr+s[x].lower()
        else:
            newstr=newstr+s[x]
    return (newstr)
    ```
