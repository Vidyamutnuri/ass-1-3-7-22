# ass-1-3-7-22
Assignment-1
n=int(input())
l=list(map(int,input().split()))
res=[]
for ind,ele in enumerate(l):
    if ele%2==0:
        res.append(ind)
print(str(res))
