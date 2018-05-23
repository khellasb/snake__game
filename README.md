# snake__game
•	Group members: Lovas Bence, Khellas Bouchra , Dilan Danial
This project describes the implementation of a Snake game, programmed in Python. In this game, the user is controlling the movement of a snake using arrow keys. The goal of the game is to navigate the snake to eat food that appears on the screen while avoiding the snake's death. The game becomes more challenging with every food eaten. The game ends if the snake crashes into the boundaries of the screen, or when the snake's head tries to cross its own body.
We decided to create several functions and split them between us! Obviously, if one of us have problems with a function, the other will help and vice-versa.
•	Description:
We will have several functions: 

•	Create a screen where the player could play the game. (Display Module)
•	Create pixels (Food) at regular interval which the Snake can eat and grow. (Display Module).
•	Create a line (Snake) which the player can control by “arrow keys”. (Calculate module).

•	Create a function which makes the Snake grow when it eat food. (Calculate module).

•	Create a function that stops the game when the snake’s head reach his tail. (Calculate module).

Secondary functions that could be create: 
•	Create a counter that count how many food the snake ate.

•	Create a database for this game. (Actually we can create a database for the snake game but we don’t know how to relate SQL and Python).

•	test the  project:
•	Function testing, each function will be tested one by one until everything works perfectly.

•	Module testing, each module (Display or Calculate) will be tested, it is very useful to see if the Display module works and not the Calculate one and vice-versa.

•	project testing , the whole project will be tested.

•	Distribution of tasks
We decided to split the work in three parts : 

•	Display module: Lovas Bence 

•	Calculate module: Khellas Bouchra Dilan Danial 

This is just a representation of the work because the display module will be easier ( I guess) than the calculate module, so both of us will do the Calculate module.

1-	Introduction :
-	The “snake game” is one of the simplest game concepts ever, with an ability that when keys are pressed in rapid succession they are all registered. This is necessary if you want to have full control of the snake at all times. 
-	The  goal is to move the snake and eat as many “food” blocks as possible. There is only one food block at any given time. When the food is eaten, the snake grows in length. If you hit the snake itself the game is over. 
-	Depending on the mode selection, the game modifies itself and hence gives the user choices as he is free to select the difficulty level. 
-	If the user wishes to quit the game anytime, He or she can press the ‘ESC’ key on the keyboard. This would directly exit the game. 
