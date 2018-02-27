# Solution
```
arr=[]
n= int(input())
for x in range(n):
    val=input().split()
    if(val[0]=='insert'):
        arr.insert(int(val[1]),int(val[2]))
    elif(val[0]=='print'):
        print(arr)
    elif(val[0]=='remove'):
        arr.remove(int(val[1]))
    elif(val[0]=='append'):
        arr.append(int(val[1]))
    elif(val[0]=='sort'):
        arr.sort()
    elif(val[0]=='pop'):
        arr.pop()
    elif(val[0]=='reverse'):
        arr.reverse()
```