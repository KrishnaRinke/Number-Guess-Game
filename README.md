# Number-Guess-Game
import random

print("......lets start a number guess game......")
n=random.randint(1,100)
a=-1
guesses=0

while(a != n):
    guesses=guesses+1
    a=int(input("enter your number:"))
    if(a>n):
        print("enter lower number please")
        
    elif(a<n):
        print("enter higher number please")
        
   
print(f"you have correctly guessed the number {n} in {guesses} guesses")
