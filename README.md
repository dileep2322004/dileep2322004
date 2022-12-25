n=int(input('enter number'))
f1=-1
f2=1
sum=0
for i in range(1,n+1):
 f3=f1+f2
 
 sum=sum+f3
 f1=f2
 f2=f3
print(sum)

    
