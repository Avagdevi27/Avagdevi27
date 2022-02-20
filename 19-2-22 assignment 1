def myprime(n):
    for i in range(2,n):
        if n%i==0:
            return False
    return True
t=int(input())
for i in range(t):
    x=input().split(' ')
    start=int(x[0])
    end=int(x[1])
    c=0
    for i in range(start+1,end):
        if myprime(i):
            c=c+1
    print(c)
