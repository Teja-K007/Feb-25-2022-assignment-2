# Feb-25-2022-assignment-2
n=int(input("enter n value:"))
l=[]
t=[]
for i in range(n):
    x=int(input())
    l.append(x)
for i in range(n):
    if l[i]!=0:
        t.append(l[i])
print("Numbers :",t)
c=0
for i in range(n):
    if l[i]!=0:
        c=c+1
print("count:",c)
