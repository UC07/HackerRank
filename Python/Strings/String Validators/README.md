# Solution
```
s = input()
for i in range(0,len(s)):
    if s[i].isalnum() is True:
        print("True")
        break
    elif(i==len(s)-1):
        print("False")
            
for i in range(0,len(s)):
    if s[i].isalpha() is True:
        print("True")
        break
    elif(i==len(s)-1):
        print("False")
    
for i in range(0, len(s)):
    if s[i].isdigit() is True:
        print("True")
        break
    elif(i==len(s)-1):
        print("False")
    
for i in range(0, len(s)):
    if s[i].islower() is True:
        print("True")
        break
    elif(i==len(s)-1):
        print("False")
for i in range(0, len(s)):
    if s[i].isupper() is True:
        print("True")
        break
    elif(i==len(s)-1):
        print("False")
```