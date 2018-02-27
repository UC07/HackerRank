# Solution
```
import textwrap
string, max_width = input(), int(input())
result = wrap(string, max_width)
print(result)

def wrap(string, max_width):
    le=0
    for x in range(len(string)):
        str=''
        if(le+max_width<=len(string)):
            for i in range(le,le+max_width):
                str=str+string[i]
            print (str)
        else:
            return string[le:len(string)]
        le=le+max_width
```