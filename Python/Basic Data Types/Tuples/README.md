```
n = int(input())
list1=list(input().split())
list2=[]
for x in range(0,len(list1)):
    list2.append(int(list1[x]))
print(hash(tuple(list2)))
```