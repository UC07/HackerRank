# Solution  
```
arr=list(input().split())
sum=0
min=1000000000
max=1
for x in range(0,len(arr)):
    num=int(arr[x])
    sum=sum+num
    if(num>max):
        max=num
    if(num<min):
        min=num
print ((sum-max),(sum-min))
```
