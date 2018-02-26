# Solution
```
n=int(input())
arr=[]
for x in range(n):
    listinput=input().split()
    di={'Name':listinput[0] , 'Maths':float(listinput[1]) , 'Phy':float(listinput[2]) , 'Chem':float(listinput[3])}
    arr.append(di)
    
username=input()

for j in range(n):
    if(arr[j]['Name'] == username):
        print("%.2f" % ((arr[j]['Phy']+arr[j]['Maths']+arr[j]['Chem'])/float(3)))
```
