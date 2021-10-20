# I have only just recently began my coding adventure, but it is my new favorite obsession

Other than the classes I am taking here at mizzou I have some self taught experience but not much

### **Languages I am comfortable with**

* Python
* HTML
* JavaScript
* Markdown

**My personal favorite program I have written is quite simple, but still fun!**

*My very own rock paper scissors game!*

```python

from random import randint


t = ["Rock", "Paper", "Scissors"]


computer = t[randint(0,2)]


player = False

while player == False:

    player = input("Rock, Paper, Scissors?")
    if player == computer:
        print("Tie!")
    elif player == "Rock":
        if computer == "Paper":
            print("You lose!", computer, "covers", player)
        else:
            print("You win!", player, "smashes", computer)
    elif player == "Paper":
        if computer == "Scissors":
            print("You lose!", computer, "cut", player)
        else:
            print("You win!", player, "covers", computer)
    elif player == "Scissors":
        if computer == "Rock":
            print("You lose...", computer, "smashes", player)
        else:
            print("You win!", player, "cut", computer)
    else:
        print("That is not a valid play.")

    player = False
    computer = t[randint(0,2)]
```
