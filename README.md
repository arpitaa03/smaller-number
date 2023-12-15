# smaller-number
def is_lesser(a,b):
    if (a< b):
        print("{} is lesser".format(a))
    elif (a>b):
        print("{} is lesser".format(b))
    else:
        print("Both numbers are equal")
a,b =map(int,input("Enter both numbers:").split())
is_lesser(a,b)
