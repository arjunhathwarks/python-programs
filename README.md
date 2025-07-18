# python-programs

def add(a,b):
    return a+b

def sub(a,b):
    return a-b

def mul(a,b):
    return a*b

def div(a,b):
    return a/b

while(True):
    print("### Simple Caluclator ###")
    print("1. ADD ")
    print("2. SUB ")
    print("3. MUL ")
    print("4. DIV ")
    print("5. QUIT ")

    choice=int(input("Enter your choice:"))
    if choice in {1,2,3,4}:
        a= int(input("Enter the 1st number"))
        b= int(input("Enter the 2nd number"))
    elif choice ==5:
        print("Quiting")
    else:
        print("enter correct choice")

    if choice==1: 
        print("The sum is ",add(a,b) )

    if choice==2:
        subtraction=sub(a,b)
        print(f"The subtraction is {subtraction}")

    if choice==3:
        multiplication=mul(a,b)
        print(f"The multiplication is {multiplication}")

    if choice==4:
        Division=div(a,b)
        print(f"The Division is {Division}")

    if choice==5:
        break
