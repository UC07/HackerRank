# Solution 
```
package main
import "fmt"

func main() {
 //Enter your code here. Read input from STDIN. Print output to STDOUT
    var n int
    fmt.Scanf("%v",&n)
    for i:=1;i<=n;i++{
        for j:=n-i;j>0;j-- {
            fmt.Print(" ")
        }
        for m:=0;m<i;m++ {
            fmt.Print("#")
        }
        fmt.Println()
    }
}
```
