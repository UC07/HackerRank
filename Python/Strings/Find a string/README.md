# Solution
```
if __name__ == '__main__':
    string = input().strip()
    sub_string = input().strip()
    
    count = count_substring(string, sub_string)
    print(count)
def count_substring(string, sub_string):
    count=0
    for x in range(len(string)):
        if(len(string)-x>=len(sub_string)):
            if(string[x:x+len(sub_string)]==sub_string):
                count=count+1
        else:
            break
    return count
```