import time
import os
import math



user=input("select the time u want in 00:00:00 format\n")
time1=user.split(':')
while 1:
    try:
        if int(time1[0])>60 or int(time1[1])>60 or int(time1[2])>60:
            user=input("00:00:00 should not be larger than 60\n")
        else:
            break
    except:
        print("you should enter in 00:00:00 format\n")
        user=input()
        time1=user.split(':')


time1=user.split(':')
trans=int(time1[0])*60*60+int(time1[1])*60+int(time1[2])

for i in range(trans,0,-1):
    os.system('clear')
    print(f"{math.floor(i/3600):02}:{math.floor((i-math.floor(i/60/60)*60*60)/60):02}:{i%60:02}")
    time.sleep(1)

os.system('clear')
print("time's up!!")
