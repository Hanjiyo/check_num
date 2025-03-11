num = int(input("Number?:"))

if num == 0:
    print("Zero")
else:
    if num > 0:
        sign = "Positive"
else:
        sign = "Negative"
if num % 2 == 0:
        print(sign, "Even Number")
else:
    print(sign, "Odd Number)
