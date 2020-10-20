print("Title of program: ni tounao you wenti ma?")
print()

counter = 0
score = 0
total_num_of_qn = 3


counter +=1
tracker = 0

while tracker !=1:
  
  print("Q"+str(counter)+") "+ "What is 77 + 33?")
  print("   a) 100")
  print("   b) 174")
  print("   c) 110")
  print("   d) 10")
  answer = input("Your answer: ")
  answer = answer.lower()
  if answer == "a":
    output = "Wrong. sha b."
    score -=1
  elif answer == "b":
    output = "Wrong. sha b."
    score -=1
  elif answer == "c":
    output = "Yes, congming de xiaohai!"
    tracker =1
    score +=1
  elif answer == "d":
    output = "Wrong. sha b."
    score -=1
  else:
    output = "yong yanjing kan xuanze, zhi neng xuanze a, b, c or d. sha b."
  
  print()
  print(output)
  print()
  print("Your current score: " + str(round((score/total_num_of_qn*100),1)) + "%"  )
  print()
  print()
  


counter +=1
tracker = 0

while tracker !=1:
  
  print("Q"+str(counter)+") "+ "chengyu 250 tiao di yi ge chengyu shi shenme")
  print("   a) anbu jiuban")
  print("   b) anfu jiuban")
  print("   c) angu jiuban")
  print("   d) anbu jiufan")
  answer = input("Your answer: ")
  answer = answer.lower()
  if answer == "a":
    output = "Yes, congming de xiaohai!"
    tracker =1
    score +=1
  elif answer == "b":
    output = "Wrong. sha b."
    score -=1
  elif answer == "c":
    output = "Wrong. sha b."
    score -=1
    
  elif answer == "d":
    output = "Wrong. sha b."
    score -=1
  else:
    output = "yong yanjing kan xuanze, zhi neng xuanze a, b, c or d. sha b."

  print()
  print(output)
  print()
  print("Your current score: " + str(round((score/total_num_of_qn*100),1)) + "%"  )
  print()
  print()
  
  

counter +=1
tracker = 0

while tracker !=1:
  
  print("Q"+str(counter)+") "+ "xiaoming hen xihuan chi xigua, ta qu tajia fujing de basha mai xigua. yili wanzheng de xigua dagai mai duo shao qian?")
  print("   a) $5.10")
  print("   b) $4.80")
  print("   c) $4.90")
  print("   d) $5.00")
  answer = input("Your answer: ")
  answer = answer.lower()
  if answer == "a":
    output = "Wrong. sha b."
    score -=1
  elif answer == "b":
    output = "Wrong.  sha b."
    score -=1
  elif answer == "c":
    output = "Wrong.  sha b."
    score -=1
    
  elif answer == "d":
    output = "Yes, congming de xiaohai!"
    tracker =1
    score +=1
  else:
    output = "yong yanjing kan xuanze, zhi neng xuanze a, b, c or d. sha b."

  

  print()
  print(output.lower())
  print()
  print("Your current score: " + str(round((score/total_num_of_qn*100),1)) + "%"  )
  print()
  print()
  
print("kaoshi wanbi. ni de tounao you wenti ma?")
  
