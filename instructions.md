## Introduction
Rock, paper, scissors is a familiar two player game that almost everyone knows how to play. It has some simple logic. Paper vs Rock, paper wins. Paper vs Scissors, scissors wins. Rock vs Scissors, rock wins. If each player chooses the same option, then it is a tie. 

## Scratch Code
Despite this being a simple game, creating it so the computer can play a user is complex. The logic has all been worked out in this blog post explanation of how this game was created in Scratch. Since Scratch is most students first coding language it is useful to see how a program is built in Scratch. Read this blog post to get some background on creating this game - [Scratch Rock Paper Scissors Blog Post](https://www.create-learn.us/blog/how-to-make-a-rock-paper-scissors-game-in-scratch/)

## Requirements
1. Python has a built-in module that you can use to make random numbers. You will need this to make the computer's choice of rock, paper, or scissors random.
   ```
   import random
   ```
2. Create a variable and input statement so the user can choose rock, paper or scissors.
3. Create a list of possible actions for the computer. The list needs a name and should include the values rock, paper, and scissors
4. Use the random.choice function to pick an item out of the list. Substitute a logical variable name and use your list name from the task above.
   ```
   variablename = random.choice(list_name)
   ```
5. Print the choices that the user and the computer made. Printing this is helpful to the user and help you debug later.
6. Determine a winner using an if - elif - else block. If you determine the tie condition first, you get rid of a lot of choices right off the bat.
7. Create a while loop so that the user can play multiple rounds. Ask the user if they want to play again at the end of the round as the condition for your while loop. 
   
