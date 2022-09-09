import random

choices = ["snake" , "water" , "gun"]
player_wins=0
comp_wins=0
for i in range(1,6):
    print(f"this is game number {i}")
    comp_choice=random.choice(choices)
    player_choice=input("choose b/w snake , water and gun \n")
    print(f"computer chose {comp_choice}")
    if comp_choice == "snake":
        if player_choice=="snake":
            print("its a draw")
        elif player_choice=="water":
            print("computer wins!")
            comp_wins+=1
        elif player_choice=="gun":
            print("you win!")
            player_wins+=1
        else: 
            print("invalid response")



    elif comp_choice == "water":
        if player_choice=="snake":
            print("you win!")
            player_wins+=1
        elif player_choice=="water":
            print("its a draaw")
        elif player_choice=="gun":
            print("computer wins")
            comp_wins+=1
        else: 
            print("invalid response")    


    elif comp_choice == "gun":
        if player_choice=="snake":
            print("computer wins!")
            comp_wins+=1

        elif player_choice=="water":
            print("you win!")
            player_wins+=1
    
        elif player_choice=="gun":
            print("its a draaw")
            
        else: 
            print("invalid response")
if player_wins == comp_wins:
    print("it was a tie! ")
    print("try again next time")
elif player_wins > comp_wins:
    print("yay you won")
else :
    print("the computer won")



