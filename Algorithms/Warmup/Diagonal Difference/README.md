# Solution
```
package main
import "fmt"
import "math"

func main() {
 //Enter your code here. Read input from STDIN. Print output to STDOUT
    var n int
    fmt.Scanf("%v \n",&n)
    arr:=make([][]int,n)
    for i:=0;i<n;i++ {
        arr[i]=make([]int,n)
        for j := 0; j < n; j++ {
            fmt.Scanf("%v",&arr[i][j])
        }
    }
    var lsum,rsum int
    lsum=0
    rsum=0
    for l:=0;l<n;l++ {
        lsum=lsum+arr[l][l]
        rsum=rsum+arr[l][n-l-1]
    }
    var nettotal float64
    nettotal=float64(lsum-rsum)
    fmt.Printf("%v",math.Abs(nettotal))       
}
```
