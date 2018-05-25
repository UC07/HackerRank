# Solution
```
package main
import "fmt"

func main() {
 //Enter your code here. Read input from STDIN. Print output to STDOUT
    var n int
    fmt.Scanf("%v \n",&n)
    arr:=make([]int,n)
    pos:=0.0
    neg:=0.0
    zero:=0.0
    for i:=0;i<n;i++ {
        fmt.Scanf("%v",&arr[i])
        if(arr[i]>0){
            pos=pos+1
        }else if(arr[i]<0){
            neg=neg+1
        }else{
            zero=zero+1
        }
    }
    fmt.Println(pos/float64(n))
    fmt.Println(neg/float64(n))
    fmt.Println(zero/float64(n))
}
```
