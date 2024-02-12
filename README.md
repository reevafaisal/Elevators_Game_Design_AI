# Elevators_Game_Design_AI
Language: C++
- Uses object oriented programming to build the following classes:
  - Person
  - Elevator
  - Floor
  - Move
  - Building
  - Game
  - SatisfactionIndex
- The elevators game allows the player to control elevators in a building to deliver the most people to their desired destination floors while minimizing the wait times (measured in anger levels) of those people.
- There are 2 streams of information that the game will process while running:
  1) A game.in file that contains all of the future events that will appear in the game.
  2) The user’s inputs determine how the elevators will move.
- With this information, the user will able to see what the current state of the Building looks like, and will be able to determine what they should command the elevators to do to respond to these incoming events.
- The Game class is the engine behind the elevators project and will be the main object used for how users interact with the program.
- AI framework is implemented in AI.cpp.
- Our AI focuses optimizing the speed and efficiency of the elevator. It combines the wants of player and optimizes the the order in which people are delivered to their respective floors.

*Due to university policy code is not publicly available but can be sent upon request.

