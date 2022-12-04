# cool-name-
# cook your dish here

a='0abcdefghijklmnopqrstuvwxyz'

t=int(input())
while(t):
    s=input()
    k=[]
    for i in s:
        k.append(a.index(i))
    k=sorted(k)
    d=0 
    for i in range(len(k)):
        d+=((i+1)*(k[i]))
    print(d)
    t-=1 
