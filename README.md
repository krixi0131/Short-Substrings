# Short-Substrings
```python
t=int(input())
for count in range(t):
    b=str(input())
    a=[]
    for i in range(len(b)):
        if i==0 or i==1:
            a.append(b[i])
            continue
        if i%2!=0:
            a.append(b[i])
    for i in range(len(a)):
        print(a[i],end="")
    print()
```
