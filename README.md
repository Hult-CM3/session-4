# session-4

def level_2():
    word1 = input("Player 1, enter your word:hi  ")
    word2 = input("Player 2, enter your word🐤 ")
    score1 = calculate_score(word1)
    score2 = calculate_score(word2)
    print(f"Player 1 score is: {score1}")
    print(f"Player 2 score is: {score2}")
    if score1 > score2:
        print("Player 1 wins!")
    elif score2 > score1:
        print("Player 2 wins!")
    else:
        print("It's a tie!")

level_2()
