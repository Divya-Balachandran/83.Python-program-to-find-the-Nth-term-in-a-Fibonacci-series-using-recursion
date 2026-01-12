def fib(n):
    if n < 0:
        print("the input is incorrect")
    elif n == 1:
        return 0
    elif n == 2:
        return 1
    else:
        return fib(n-1) + fib(n-2)

print(fib(7))




OUTPUT:

8
