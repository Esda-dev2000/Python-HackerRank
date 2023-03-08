# pythonQ
print("welcome to my computer quiz!!!")

playing = input("do you want to play??")

if playing !="yes":
    quit()

print("Okay! lets Play!! :)")
score = 0

answer = input("is the coding lanaguage Python, named after a snake? ")
if answer == "no":
    print('correct!')
    score +=1
else: 
    print('incorrect!') 

answer = input("what does CPU stand for???") 
if answer == "central processing unit":
    print('correct')
    score +=1
else:
    print('incorrect')

answer = input("what does GPU stand for?") 
if answer == "graphics processing unit":
    print ('correct')
    score +=1
else:
    print ('incoreect')

answer = input("what does RAM stnad for??") 
if answer == "random acess memory":
    print ('correct')
    score +=1
else:
   print ('incorrect')

print("you got" + str(score) + " questions correct!!")
print("you got" + str((score/4) *100) + "%. ")
