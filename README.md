# program-64
year = int(input("Enter a year: "))

if (year % 4) == 0:
    if (year % 100) == 0:
        if (year % 400) == 0:
            print(year, "is a leap year")
        else:
            print(year, "is not a leap year")
    else:
        print(year, "is a leap year")
else:
    print(year, "is not a leap year")

Output:
Enter a year: 2006
2006 is not a leap year

Enter a year: 1980
980 is a leap year

Pgm 83:
def Fib(n):
    if n < 0:
        print("The input is incorrect.")
    elif n == 1:
        return 0
    elif n == 2:
        return 1
    else:
        return Fib(n-1) + Fib(n-2)

print(Fib(7))

Output;
8
