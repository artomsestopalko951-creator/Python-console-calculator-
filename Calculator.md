# Python-console-calculator-
#Just a calculator bro
try:
    n1 = int(input("enter 1nd number "))
    wtd = input("what to do? +, -, * or ×, / ? ")
    n2 = int(input("enter 2nd number "))

    if wtd == "+":
        print(n1 + n2)
    elif wtd == "-":
        print(n1 - n2)
    elif wtd == "*" or wtd == "×":
        print(n1 * n2)
    elif wtd == "/":
        if n2 == 0:
            print("Error: division by zero!")
        else:
            print(n1 / n2)
    else:
        print("bro what a u doing?")

except ValueError:
    print("enter a number! not text!")
