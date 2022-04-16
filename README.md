# twosum

```
def twosum(lst, target):
  
  for i in range(0, len(lst)):
     for j in range(i+1, len(lst)):
        if lst[i] + lst[j] == target:
          return [i, j]
lst = list(map(int, input().split()))
target = int(input())

final = twosum(lst, target)

print(final)
```
