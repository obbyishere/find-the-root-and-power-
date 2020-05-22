# find-the-root-and-power-
x=int(input("plase write a number: "))
root= x**0.5

for i in range(6):
    pwr= root**i
if pwr == x:
    print(pwr)
    break
else:
    print("there's no perfect pwr")
print(root)
