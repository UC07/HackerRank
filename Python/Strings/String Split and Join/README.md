# Solution
```
line = input()
result = split_and_join(line)
print(result)

def split_and_join(line):
    li=line.split()
    return "-".join(li)
```