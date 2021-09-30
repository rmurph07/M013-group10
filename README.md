# project-1
ECS 101 Project #1

7 long bits and 4 short bits 

def convert_binary(x: str):
    ans = ""
    for i in x:
       if i == "a":
           ans += "101"
       elif i == "b":
           ans += "111"
       elif i == "c":
           ans += "1001"
    y = ans.count("1") + ans.count("0")
    y = str(y)
    ans = y + "." + ans
    print(ans)
convert_binary("abcbab")
