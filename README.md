# uncle-little-colins-game
text based python game for kids for xmas


Greetings, from your dear old Uncle Little Colin!

Below are the instructions for running 'uncle little 
colins super awesome very good special remazable gamesplosion'

The coolest game around.

This text based computer game was programmed specially for you
and involves our family! You can play the game, learn the 
raspberry pi (computer)by trying different ways of running 
the game, and learn some programming by changing the games 
programming once you're done playing it!!!



Instructions:



...To run the game...

-Double click on the 'Run The Game.sh' file. 
	This will open a prompt asking what you want to do
	with the file.
-Run the game in a terminal by pressing 'Enter'
	or by clicking 'Execute in Terminal'






...AT THIS POINT TRY TO PLAY THE GAME...

IF YOU GET STUCK OR

ONCE YOU HAVE PLAYED THE GAME TO YOUR HEARTS DESIRE 

PROCEED BELOW FOR FURTHER INSTRUCTIONS AND THINGS TO TRY






...Fun alternatives for running the game...

You can open the file in a terminal window by
-Open a terminal window by clicking the black 'terminal' box 
	at the top of the screen or by holding down 
	ctrl + alt + T
-Type or copy/paste the following line of code- 
	fyi not counting the parentheses 
	[python3 /home/pi/Desktop/'Uncle Little Colins Game'/'uncle little colins super awesome very good special remazable gamesplosion.py']

You can run the file in a Python Integrated Development Environment (IDE) by
-Double clicking the file 'uncle little colins super awesome very good special remazable gamesplosion.py'
-Click 'Run' at the top of the window that opens
-This should run the game in the consol at the bottom 
	of the window


...Things to know about the game...

-If the game is asking for input and the prompt has numbers 
	enter a number
	(e.g. if it says "1-hello 2-goodbye" 
	type "1" and hit Enter)
-If the game is asking for input and the prompt has only text
	then type out the response 
	(e.g. if it says "(yes or no)" 
	type "yes" and hit Enter)
-You have to fight and defeat the monster at the house 
	the person is at in order to win
-The missing person will only be at one (randomly selected)
	house so if you haven't found them keep looking!
-To fight the monsters you will be given 3 weapon options
	one weapon will be the monsters weakness
		this will defeat the monster
	one weapon will be the monsters strength
		this will cause you to run away
	one weapon will be neither a strength nor weakness
		this will ask you to try another weapon




...Things to try once you have beaten the game a bunch of times...

CHANGE THE PROGRAMMING!!!

Open the code for the game in a python 
	Integrated Development Environment (IDE) by double clicking
	Double clicking the file 'uncle little colins super awesome very good special remazable gamesplosion.py'
	located in the 'Uncle Little Colin's Game' folder

Anything in the file with a '#' at the front is a comment to
	help you understand what the code is doing

Once something is changed save the file and either rerun the
	game using the main method above, or run it in the
	IDE by clicking 'run'. If you recieve an error you need
	to figure out what caused it!


#BEGINNER


..Change the flow of the game..
-at the top of the file (lines 6 and 7)
	you will see two variables called
	'shortPause' and 'longPause'. These variables set the
	number of seconds the game waits before delivering
	the next line of text.
-change these variables to different numbers in order to change
	how fast or slow the game moves



..Change the what happens what the game says when a monster is

.defeated
change the text on lines 298, and 327

.no effect
change the text on lines 253, 311, and 336

.not defeated
change the text on lines 307, and 332




#INTERMEDIATE


..Change who is in the game..
-at the top of the file (lines 10 through 25)
	you will see a list of people in the game
	you can add, delete, or change who is in the game
	by changing this list
-specific task1: 
	change "Uncle Steve" on line 23 to
	"Ninja Blade Master of Shadow" and play the game until
	that's the name that's missing! (helpful hint: change
	the pause variables to both be zero, and answer 'no'
	to 'do you know this person', if it's not him.
	this will speed up the process
-specific task2:
	you can make the game always choose the same person by 
	-typing '#' in front of nameChoice on line 118
	-deleting the '# ' at the beginning of line 120
	-change the name in the quotes on line 120 to 
	whoever you want



#ADVANCED

..Change the weapons to whatever you want..
-at the top of the file (lines 47 through 56)
	you will see a list of weapons in the game
	you can add, delete, or change these
	by changing this list
-a lot of things depend on these weapons so
	remember, if you change the weapons you will want to also change
	which weapons are the monsters weaknesses (code lines 59-68),
	monsters strengths (code lines 71-80), what happens when
	the monster is defeated (code lines 83-100), and what happens
	when the monter is not defeated (code lines 103-115). an
	the weapons on lines 213-222.
-important note for the weaknesses and strengths. they are
	all matched in their index number and index numbers
	start at zero (for example in a list
	of ["bug spray", "shark sword", "silly string"]).
	so the index 0 is 'bug spray', 1 is 'shark sword', 
	and 2 is 'silly string'. In order to make sure that 
	your code runs each monster needs one strength and 
	one weakness,and you match index number for the list 
	of weapons to the monsters strength/weakness. 
	For example, if the first monster was weak against 
	silly string the second against shark sword, 
	and the third against bugspray then the list of 
	weaknesses would be [weapon[2],weapon[1],weapons[0]]

	

	
