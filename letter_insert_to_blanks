import letter_checker.py

display = []
blank = "_"
display.extend(len(chosen_word) * blank)
print(display)
  
guess = input("Guess a letter: ").lower()

for i in range(len(chosen_word)):
  letter = chosen_word[i]
  if letter == guess:
    display[i] = letter
    print("Right")
  else:
    print("Wrong")
print(display)
