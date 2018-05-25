# Solution  
```
package main
import "fmt"

func main() {
 //Enter your code here. Read input from STDIN. Print output to STDOUT
    var n int
    fmt.Scanf("%v \n",&n)
    x := make([]int, n)
    sum:=0
    for i:=0;i<n;i++ {
        fmt.Scanf("%v",&x[i])
        sum=sum+x[i]
    }
    fmt.Printf("%v",sum)
}
```
