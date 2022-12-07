import random
def is_prime(n):
    if n==2 or n==0:
        print(f'{n} is neither prime no composite')
    elif n>0:
        for i in range(2,n):
            if n%i==0:
                return print(f'{n} is a composite number')
            else:
                return print(f'{n} is a composite number')
    else:
        print(f'{n} is a negative number and negative numbers can\'t be prime or composite')
a=int(input()) ; b=int(input())
c=random.randrange(min(a,b),max(a,b))
print(c)
if c>0:
    print(f'{c} is a positive number')
elif c==0:
    print(f'{c} is zero')
else:
    print(f'{c} is a negative number')
if c%2==0:
    print(f'{c} is even')
else:
    print(f'{c} is odd')
is_prime(c)
