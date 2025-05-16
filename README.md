a=float(input("enter a value:"))
b=float(input("enter b value:"))
op=input("enter operator(+,-,*,/):")
if op=='+':
    print(a+b)
elif op=='-':
    print(a-b)
elif op=='*':
    print(a*b)
elif op=='/':
    if b!=0:
        print(a/b)
    else:
        print("invalid input")
else:
    print("invalid operator")

loop=0
while loop<=10:
    print(loop)
    loop+=1


    loop=0
while loop<=10:
    print("aiswarya",end=' ')
    loop+=1

    loop=0
while loop<=10:
    print("aiswarya",end=' ')
    print("sahani",end=' ')
    loop+=1

    n=int(input("enter number"))
sum=n*(n+1)//2
print(sum)

#while
n=int(input("enter number"))
i=1
sum=0
while i<=n:
    sum=sum+i
    i=i+1
print(sum)

n=int(input("enter he number"))
i=n
while i>=1:
    print(i,end=' ')
    i=i-1

    num=int(input("enter the number"))
rev=0
print(num)
while num>0:
    d=num%10
    rev=rev*10+d
    num//=10
    print(rev)
