def start_game():
  print("Welcome to the Adventure Game!")
  print("You find yourself in a dark forest.")
  print("You see two paths: one to the left and one to the right.")
  choose_path()

def choose_path():
  choice = input("Do you go left or right? (left/right): ").lower()
  if choice == "left":
      go_left()
  elif choice == "right":
      go_right()
  else:
      print("Invalid choice. Please choose left or right.")
      choose_path()

def go_left():
  print("You walk down the left path and encounter a river.")
  print("You can either swim across or try to find a bridge.")
  choice = input("Do you swim or find a bridge? (swim/bridge): ").lower()
  if choice == "swim":
      print("You swim across the river but are attacked by a crocodile. Game Over!")
  elif choice == "bridge":
      print("You find a rickety bridge and carefully cross it. You continue your adventure.")
      continue_adventure()
  else:
      print("Invalid choice. Please choose swim or bridge.")
      go_left()

def go_right():
  print("You walk down the right path and find a cave.")
  print("Do you enter the cave or continue past it?")
  choice = input("Enter the cave or continue? (enter/continue): ").lower()
  if choice == "enter":
      print("You enter the cave and find a treasure chest! You win!")
  elif choice == "continue":
      print("You continue past the cave and get lost in the forest. Game Over!")
  else:
      print("Invalid choice. Please choose enter or continue.")
      go_right()

def continue_adventure():
   print("You come to a fork in the road.")
   choice = input("Do you go north or south? (north/south): ").lower()
   if choice == "north":
       print("You travel north and find a friendly village. Congratulations, you have completed your adventure!")
   elif choice == "south":
       print("You travel south and encounter a dragon. Game Over!")
   else:
       print("Invalid choice. Please choose north or south.")
       continue_adventure()

start_game()
