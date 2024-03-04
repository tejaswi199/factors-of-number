#approach 1
n=int(input())
for i in range(1,n+1):
  if(n%i==0):
    print(i,end=" ")
#approach 2
n=int(input())
i=1
while(n>=i):
  if(n%i==0):
    print(i,end=" ")
  i=i+1
