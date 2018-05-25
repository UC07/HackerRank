# Solution  
```
package main
import "fmt"

func main() {
 //Enter your code here. Read input from STDIN. Print output to STDOUT
    var alice int
    var bob int
    xalice:=make([]int, 3)
    fmt.Scanf("%v %v %v",&xalice[0],&xalice[1],&xalice[2])
    xbob:=make([]int, 3)
    fmt.Scanf("%v %v %v",&xbob[0],&xbob[1],&xbob[2])
    for i:=0;i<3;i++ {
        if(xalice[i]>xbob[i]){
            alice=alice+1
        }else if(xalice[i]<xbob[i]){
            bob=bob+1
        }
    }
    fmt.Printf("%v %v",alice,bob)
}
```
