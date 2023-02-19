rock = '''
    _______
---'   ____)
      (_____)
      (_____)
      (____)
---.__(___)
'''

paper = '''
    _______
---'   ____)____
          ______)
          _______)
         _______)
---.__________)
'''

scissors = '''
    _______
---'   ____)____
          ______)
       __________)
      (____)
---.__(___)
'''

#Write your code below this line 👇
import random
choise=int(input("ENTER YOUR CHOISE 0 for ROCK or 1 for PAPER or 2 for SCISSORS  "))
if choise==0:
  print(rock)
elif choise==1:
  print(paper)
elif choise==2:
  print(scissors)
else:
  print("WRONG CHOISE")

  
set=[rock,paper,scissors]
length=len(set)
L=random.randint(0,length-1)
print(set[L])
if(L==choise):
  print("DRAW ")
  
elif L==0 and choise==1:
  print("PAPER DEFEATS ROCK\n YOU WINS!!")
elif L==0 and choise==2:
  print("SCISSORS ARE DEFEATED BY  ROCK\n YOU LOSE!!")
  
elif L==1 and choise==0:
  print("ROCK IS DEFEATED BY PAPER\n YOU LOSE!!")
elif L==1 and choise==2:
  print("SCISSORS DEFEATS PAPER\n YOU WINS!!")  

elif L==2 and choise==0:
  print("SCISSORS ARE DEFEATED BY ROCK\n YOU WIN!!")
elif L==2 and choise==1:
  print("SCISSORS DEFEATS PAPER\n YOU LOSE!!")  
