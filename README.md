# rock-paper-scissors
the Rock Paper Scissors game, and it uses the Random module
##ROCK PAPER SCISSORS GAME W/ RANDOMIZED COMPUTER INPUT
##SO YOU'RE COMPETING WITH THE RANDOMIZED



#ASCII art


#you can do the if else statement as you see below for the player1 variable
##or you can also store these moves as a list
    ##this also makes sense since rock is alraedy defined by 0 (in input and order in list)



#remember: \n creates a nice linebreak, which looks good for the user input of this question
#it's at this point that you can put - print(moves[player1]) - so that it prints the 0,1,2 selection
    ##of the user input


#remember: if you're inputting a variable that's an integer, you need it to be an f-string
#you see how you can print the [order/computer input] taken from the moves list, now that
    ##the moves list has been defined by the order of the moves, and the convenient
    ##selection options of 0,1, and 2?



#computer > player means computer won, except there are exceptions
#instead of starting with that grand statement, we start the IF statement with the exceptions
    #first before you get into the big "computer > player" statement (put in as elif)
#the int(player) here could have been used when as created the variable itself - int(input)
    #but oh well
#the "Invalid Number" line is also at the top because you want it to be checked first...
    #if someone put in an invalid number, it shouldn't go through the other lines first...
    ###it's invalid no matter what, so it goes first
