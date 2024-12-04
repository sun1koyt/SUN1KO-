**from random import*

a=randint(10,1000)
b=randint(10,1000)
print("1.  x+3=5")
print("2   5-x=2")
print("3.  5*x=20")
print("4.  20:x=5")
k=int(input("qanday tenglama tuzishni xoxlaysiz"))
if k==1:
    print(a,"+ x =",b)
    n=int(input("Tenglama yechimini kirit x= "))
    if n==b-a:
        print("Javobingiz to'g'ri")
    else:
        print("Javobingiz noto'g'ri")
if k==2:
    print(a,"- x =",b)
    n=int(input("Tenglama yechimini kirit x= "))
    if n==a-b:
        print("Javobingiz to'g'ri")
    else:
        print("Javobingiz noto'g'ri")
if k==3:
    print(a,"* x =",b*a)
    n=int(input("Tenglama yechimini kirit x= "))
    if n==b:
        print("Javobingiz to'g'ri")
    else:
        print("Javobingiz noto'g'ri")        
if k==4:
    print(a,": x =",a*b)
    n=int(input("Tenglama yechimini kirit x= "))
    if n==b:
        print("Javobingiz to'g'ri")
    else:
        print("Javobingiz noto'g'ri")        

        

**
