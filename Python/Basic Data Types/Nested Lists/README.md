# Solution
```
n=int(input())
arr=[]
for x in range(n):
    name=input()
    marks=float(input())
    l=[name,marks]
    arr.append(l)
se=set()
for i in range(n):
    se.add(arr[i][1])
li=list(se)
li.sort()
sm1=li[1]
lipr=[]
for j in range(n):
    if(arr[j][1]==sm1):
        lipr.append(arr[j][0])
lipr.sort()
for x in range(len(lipr)):
    print (lipr[x])
```