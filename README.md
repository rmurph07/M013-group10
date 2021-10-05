# project-1
ECS 101 Project #1

7 long bits and 4 short bits 

def findcode(x: str):
    ans = ""
    for i in x:
       if i == "a":
           ans += "11011"
       elif i == "b":
           ans += "0000001"
       elif i == "c":
           ans += "0000011"
       elif i == "d":
            ans += "0000111"
       elif i == "e":
           ans += "10010"
       elif i == "f":
           ans += "0001111"
       elif i == "g":
           ans += "0011111"
       elif i == "h":
           ans += "0111111"
       elif i == "i":
           ans += "11111"
       elif i == "j":
           ans += "0000010"
       elif i == "k":
           ans += "0000100"
       elif i == "l":
           ans += "0001000"
       elif i == "m":
           ans += "0010000"
       elif i == "n":
           ans += "0100000"
       elif i == "o":
           ans += "10100"
       elif i == "p":
           ans += "0000101"
       elif i == "q":
           ans += "0001010"
       elif i == "r":
           ans += "0010101"
       elif i == "s":
           ans += "0101011"
       elif i == "t":
           ans += "0000110"
       elif i == "u":
           ans += "11001"
       elif i == "v":
           ans += "0001100"
       elif i == "w":
           ans += "0011000"
       elif i == "y":
           ans += "10000"
       elif i == "z":
           ans += "0110000"
       elif i == "x":
           ans += "0000111"
    y = ans.count("1") + ans.count("0")
    y = str(y)
    ans = y + "." + ans
    print(ans)
findcode("")
