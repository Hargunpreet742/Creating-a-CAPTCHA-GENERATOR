# Creating-a-CAPTCHA-GENERATOR
Create a captcha generator using python




import random
txt = "abqwyioppdfhjklzxvnmABHHHFSGSHHDQIIIOPASGJKLZBXN"
t = ""
for i in range(5):
    a = int(random.random() * len(txt))
    t += txt[a]
print(t)


