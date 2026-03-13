# Command The Dungeon!

## Elevator Pitch

You are stuck in a dungeon, and you don't know how you got there. You cannot move your legs; instead, you are presented with a text box and a paper that says "use the cd to escape". Your objective is to escape the dungeon using the cd command, picking up variations of it, and different commands along the way to help you with your escape.

## Influences (Brief)

- 3D Monster Maze:
  - Medium: PC Game
  - Explanation: Its visuals simulate a 3D environment; however, it is only 2D images. It is the type of aesthetic we tried to achieve with this game.
- Colossal Cave Adventure:
  - Medium: PC Game
  - Explanation: The game shows how actions written in a text section make the character perform actions. This was our reference for our mechanic of moving using terminal commands.

## Core Gameplay Mechanics (Brief)

- Move through the dungeon by writing the name of the passages in front of you, using the "cd" terminal command in a text box.
- The passage name written with the "cd" command must be written with appropriate casing and syntax.
- Return to the previous room you were in by using the "cd .." command properly.
- When the "cd" command is properly written, the player will move to another room/scene, where it can be a new passage or a room.
- When entering any room/passage, the player can write the "ls" command to inspect their current location.
- The player can also write the "ls -a" command to unravel possible secrets hidden in the rooms/passages.
- Entering a command with wrong syntax will result in a message indicating what has been written wrong.
- The player will need to find certain objects to open specific doors to escape the dungeon.
- When the player escapes the dungeon, the game changes into a new scene, indicating that the player has won.

# Learning Aspects

## Learning Domains

Correct use and implementation of terminal commands "cd" and "ls", including variations and different forms such as "cd .." and "ls -a".

## Target Audiences

- Novice programmers with little to no knowledge of navigating a terminal.
- Aimed for early university students and advanced high school students.

## Target Contexts

- The game would be assigned as a practice, which would then be tested to see if students were able to comprehend the use of both "cd" and "ls" commands.
  
## Learning Objectives

*Remember, Learning Objectives are NOT simply topics. They are statements of observable behavior that a learner can do after the learning experience. You cannot observe someone "understanding" or "knowing" something.*

- Write commands in the console to navigate to a folder in the current directory
- Write commands in the console to navigate to a folder in the parent directory
- Write commands in the console to find and navigate to a hidden file in the current directory

## Prerequisite Knowledge

*What do they need to know prior to trying this game?*

- Write words on the keyboard
- Explain what cd is meant to do
- Explain what ls is meant to do
- Explain what mov is meant to do

## Assessment Measures

*Clearly identify a set of viable assessment questions AND their grading logic. The questions should be specific examples of the kinds of questions that your game could conceivably improve student performance on. For the grading logic, it could be the correct answer, a rubric for evaluating the answer, or exact logic for deriving answers.*

Write the console commands you would use to do the following:
- Find file names in your folder *Answer: ls*
- Enter a folder names a within the current folder *Answer: cd a*
- Return to the parent folder *cd ..*
- Find the name of the hidden file in your folder *ls -a*
- Move a file from one place to another.

# What sets this project apart?

*Give some reasons why this game is not like every other game out there. Whether the learning objective is unique, the gameplay mechanics are new, or what. You should persuade the reader that your game is novel and worthy of development. Consider arguments that would be persuasive to a Venture Capitalist, Teacher, or Researcher. These might be focused on learning needs, too.*

- *Reason #1*
- *Reason #2*
- *Reason #3*
- *Reason #4*
- *etc.*

# Player Interaction Patterns and Modes

## Player Interaction Pattern

Single player game. The player controls their movements and actions through writing terminal commands.

## Player Modes

- Single Player: Player moves around the dungeon, looking for items to open doors and, eventually, escape.
- Main Menu: The player will see a start menu which will allow them to start the game, quit it, and adjust the volume.

# Gameplay Objectives

- Gather key items:
    - Description: When key items are collected, the player will be able to open doors and advance to new areas. 
    - Alignment: *Describe how this aligns with one or more learning objectives*
- Gather mask pieces:
    - Description: When the player gathers all the pieces of a mask, it will open the final door, which will allow the player to escape the dungeon.
    - Alignment: *Describe how this aligns with one or more learning objectives*
- Collect new commands:
    - Description: The player will gather small notes that will allow him to introduce new commands in the text box, doing new things.
    - Alignment: *Describe how this aligns with one or more learning objectives*

# Procedures/Actions

- A text box will be presented for the player to input terminal commands.
- Passage names represent files found in directories in a terminal command.

# Rules

- If the player enters the right "cd" command with an existing passage/room name, it will change scenes to a new passage/room with new names.
- If the player enters the right "ls" command with an existing passage/room name, the player is shown what things they can interact with.
- If the player enters the right "mov" command with an existing Object name, the player be able to put that object in its items, or use it somewhere else..
- If the player enters either the "cd", "ls", or the "mov" command, or any of its variations, command incorrectly, an error message appears that says "Command does not exist".
- If the player enters the "cd .." command, the player will be sent back to the previous passage/room they have previously been in.
- If the player enters the "ls -a" command, the player is shown what things they can interact with, plus secret things not shown with "ls".
- An incorrect passage name will result in a text saying "There's no passage with that name".
  
# Objects/Entities

- An interactable live skeleton that makes a variable true for the player to use the "ls -a" command.
- An interactable mask that provides the player with the main goal of the game.
- A text box in the lower center of the screen where the player can write the commands.
- Doors that will require keys in order to be open.

## Core Gameplay Mechanics (Detailed)

- Write commands in the text box and press enter to use it.
    - ls: To inspect the current area.
    - cd: To move from one space into another.
    - mov: To move an object from one space to another.
- Doors will require specific items to open them.
- Player will use enter to keep dialogue going when talking to entities.
- Talking to entities can unravel more story, or award new abilities.
- Player will be able to grab objects and store them for later use.
- Collect 4 pieces of a mask to open the final door.

    
## Feedback
At certain points in the game, they will be shown commands to be introduced to them. After that, using something other than those commands would be beyond the scope of the game, but using commands incorrectly would give some feedback. For example, cding to a nonexistent folder would show an error that the folder doesn't exist and probably hint at using ls.

# Story and Gameplay

## Presentation of Rules
- 
*Briefly describe how the player will learn the gameplay mechanics. Avoid using walls of text, since people will not read them. Think instead of natural ways of teaching mechanics iteratively and slowly.*
- The core gameplay mechanics are simple so rather than worrying about them forgetting or ignoring what they are, the game will slowly give the player the chance to learn how to apply it hands on. Small hints and directions may be given to make it easier for players newer to the topic to deduce the correct command.

## Presentation of Content
- 
*Briefly describe how the player will be taught the core material they are meant to learn. Avoid using walls of text, since people will not read them. Think instead of natural ways of teaching material iteratively and slowly.*
- They will briefly be introduced to one mechanic at a time and slowly spend time applying that mechanic. Repeatedly using a few major mechanics should be good for memory.

## Story (Brief)

You are trapped in an unknown dungeon, and you are incapacitated. You must use command terminals to get out.

## Storyboarding
- 
*Go into as much detail as needs be to visually convey the Dynamics of your game. Be detailed. Create storyboards and freeze frame images that concisely capture important key elements of your game. You are strongly recommended to sketch pictures on paper and embed them here. Be sure make it clear how previously-described mechanics come through in the dynamics.*
- 

# Assets Needed

## Aethestics

The game should be a simple pixel art, but one that simulates that the player is in a 3D space, simulating a dungeon. It should be visually appealing enough so that the player wants to explore it.

## Graphical

- Characters List
  - Skeleton in room: Should be in a sitting position, and be composed of two parts: Body, which remains static, and skull, which will have two frames, indicating that it is talking.
  - *Characters 2*
  - *...*
- Textures: N/A
- Environment Art/Textures:
  - Walls: Should replicate an old stone brick wall. Not many details, but enough to make it look rocky.
  - Floor: The floor should follow the same logic as the wall.
  - Doors: The doors are to represent that they are made out of wood, and simulate old medieval doors with an arch at the top. They should have a door handle for more immersion.
  - Final door: The final door will have the same design as the normal doors, with the difference that it will have a hole in the center, where a mask would go and unlock it.


## Audio


*Game region/phase/time are ways of designating a particularly important place in the game.*

- Music List (Ambient sound)
  - *Game region/phase/time*: *Example 1*, *Example 2*
  - *Game region/phase/time*: *Example 3*, *Example 4*
  
*Game Interactions are things that trigger SFX, like character movement, hitting a spiky enemy, collecting a coin.*

- Sound List (SFX)
  - *Game Interaction*: *Example 1*, *Example 2*
  - *Game Interaction*: *Example 3*, *Example 4*


# Metadata

* Template created by Austin Cory Bart <acbart@udel.edu>, Mark Sheriff, Alec Markarian, and Benjamin Stanley.
* Version 0.0.3
