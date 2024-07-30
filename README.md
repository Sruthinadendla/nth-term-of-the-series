# nth-term-of-the-series
from math import pow
n=int(input())
x,y=1,1
if n%2==0:
  n=n//2
  print(int(pow(3,n-1)))
else:
  n=n//2+1
  print(int(pow(2,n-1)))
  
