# MLB-Wins-Predictor
Taking statistics of individual players to predict how many games a baseball team will win

H = int(input("Hits the players has: "))
BB = int(input("Walks the player has: "))
CS = int(input("Times caught stealing: "))
TB = int(input("Total bases: "))
SB = int(input("Stolen Bases: "))
AB = int(input("At Bats: "))

A = H + BB - CS
B = (TB + ((.55)*(SB)))
C = AB + BB
RC = (A*B)/C
print(RC)
