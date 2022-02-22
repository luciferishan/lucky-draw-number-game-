# lucky-draw-number-game-
import random
n=random.randint(1,100)
print("you have 5 chances to win this lucky draw")
for a in range(1,6):
    print(a,":chance")
    uinp=int(input("enter a number between 1 to 100 :-"))
    if uinp>n:
        print("computer number:",n)
        print("zada bada number le liya thoda chota karo")

    elif uinp<n:
        print("computer number:", n)
        print("bahut chota hai aapka number thoda bada number lo")

    else:
        print("computer number:", n)
        print("congo! tera number match kar gaya")
        break


