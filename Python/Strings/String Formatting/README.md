# Solution
```
def print_formatted(n):
    w = len(format(n, 'b'))
    for i in range(1, n + 1):
        print(str(i).rjust(w), format(i, 'o').rjust(w), format(i, 'X').rjust(w), format(i, 'b').rjust(w))
```
