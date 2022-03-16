#Future value calculator with rounding to 3 significant figures

import math

def growsigfigs():
    print(" ")
    print("Growth calculator, rounded to 3 significant figures.")
    print(" ")
    print("Uses Present Value*(1+i)^n to calculate the future value of the sum invested.  Takes that amount and rounds it to 3 significant figures using-")
    print(" ")
    print("     size=int(log(FV)/log(10))")
    print("     factor=10^(size-2)")
    print("     sigfigs=int(x/factor)*factor")
    print(" ")
    print(" ")

    pv = eval(input("Enter the starting amount: "))
    i = eval(input("Enter the annual interest rate: "))
    n = eval(input("Enter the number of years: "))

    fv = pv * (1 + (i/100))**n

    size=math.floor(math.log10(fv))/math.log10(10)
    factor=10**(size-2)
    sigfigs=math.floor(fv/factor)*factor

    print(" ")
    print("The amount after", n, "years at", i,"% is", sigfigs)    
   
growsigfigs()