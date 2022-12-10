# quize-game-mini-project
#quize game mini project
print("welcome to my pc quize!")
playing = input("DO YOU WANT TO PLAY? ")
if playing.lower()!="yes":
  quit()
else:
    print("okay! let's play :)")
    socre =0
answer = input("what dose cpu stand for? ")
if answer.lower() == "control procssing unit":
    print("correct! you are doing good")
    socre +=1
else:
    print("incorrect! ")
answer = input("what dose gpu stand for? ")
if answer.lower() == "graphical procssing unit":
    print("correct! you are doing good")
    socre +=1
else:
    print("incorrect! ")
print("you got"+str(socre)+"question correct! ")
print("you got"+str((socre / 2) * 100)+"%")
