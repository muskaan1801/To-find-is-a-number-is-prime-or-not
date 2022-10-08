# To-find-is-a-number-is-prime-or-not
def is_Prime(n):
    flag = True
    for i in range(2,n//2):
        if(n%i == 0):
            flag = False
            break
        else:
            continue
    return flag        

n = int(input("\nEnter the number: "))
res = is_Prime(n)
if(res):
    print("\nNumber is prime")
else:
     print("\nNumber is not prime")
