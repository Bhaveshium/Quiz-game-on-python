# Quiz-game-on-python

print("Welcome to  my computer quiz!")

playing=input ("Do you want to play? \n").lower()
if playing.lower() !="yes":
    quit()

print("okay! Let's play :) ")
score = 0

answer =input ("What does CPU stands for?\n").lower()
if answer == "central processing unit":
    print("Correct!")
    score +=1
else:
    print("Incorrect!")

answer =input ("What does RAM stands for?\n").lower()
if answer == "random access memory":
    print("Correct!")
    score +=1
else:
    print("Incorrect!")

answer =input ("What does GPU stands for?\n").lower()
if answer == "gaming processing unit":
    print("Correct!")
    score +=1
else:
    print("Incorrect!")

answer =input ("What does PSI stands for?\n").lower()
if answer == "power supply":
    print("Correct!")
    score +=1
else:
    print("Incorrect!")

print("You got " + str(score)+ "questions correct!")

print("Your score is " + str((score/4)*100) +"%.")

#coded by Bhavesh#








