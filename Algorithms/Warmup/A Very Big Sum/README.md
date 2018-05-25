# Solution
```
package main
import "fmt"

func main() {
 //Enter your code here. Read input from STDIN. Print output to STDOUT
    var n int
    fmt.Scanf("%v",&n)
    arr:=make([]int,n)
    sum:=0
    for k:=0;k<n;k++ {
        fmt.Scanf("%v",&arr[k])
        sum=sum+arr[k]
    }
    fmt.Printf("%v",sum)
}
```
