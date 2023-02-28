In this project I am building a "rock, paper, scissors" game. This is a hand game for two or more players. Participants say “rock, paper, scissors” and then simultaneously form their hands into the shape of a rock (a fist), a piece of paper (the palm of a hand, or a pair of scissors (two fingers extended). The rules are the following:
  
   •	Rock smashes scissors.
   •	Paper covers rock.
   •	Scissors cut paper.
   
The project will be created using python and an image model.
Python:
-	To arbitrary generate the computer’s choices, I imported the random module: <import random>
-	For simplicity, this task and the following will be stored in a function that can be called when necessary: def get_computer_choice():
-The computer will randomly choose one of the options: 
   
 possible_choices = ["rock", "paper", "scissors"]
 computer_choice = random.choice(possible_choices)
 print(computer_choice)
