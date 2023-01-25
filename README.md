# day-7
a=list(map(int,input().strip().split()))
n=0
s=0
for i in a:
    fs=max(i+s,n)
    s=n
    n=fs
print(n)
