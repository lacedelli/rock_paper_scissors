

Rock, paper, scissors project:

Expectations going in:
	
	I expect this project to be relatively simple in that 
	making a bot that selects an option out of three isn't a 
	herculean task, however, I expect the logic of the game itself
	to be the biggest obstacle, since I want to try and find the
	most elegant way to handle the logic but I have no idea
	what that even looks like!

	The main idea that I have right now about how to make the 
	game logic work is with either a series of if blocks or 
	"?" logic operators that firstly determine the data inputted
	from the player and from that point, check for the data the
	"ai" chose, determining if the player won or lost.

	27/July/2019.


Thoughts after finishing the project:

	Not to sound like I'm bragging or anything, but the project was
	overall a breeze, played a liite bit with ternary logic 
	--knowledge of which to me was a little bit shaky beforehand--
	and it worked on the first try! Of course, returning a string
	is a lot simpler than any other operation, but it's a start!
	
	The main problem I encountered was with the handling of scope,
	which still gives me a couple headaches here and there.
	The variables which hold the score for the player and the pc 
	originally were intended to be contained within the game() 
	function, but they were not being updated by playRound(), so
	I just did the simplest fix I could think of: making them both
	global variables.

	28/July/2019.
