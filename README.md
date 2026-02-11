## W1

### Activity 1
One piece of advice is to not procrastinate!

More advice:
- Read the pre-learning slides
- Use out of class tools (YouTube / Unity documents)
- Take advantage of support when in need of assistance: peers, LAs, Office hours and discord
- Ask questions
- Learn how to use the inspector
- Create map concepts 
- make sure your itch links work for the love of god


### Activity 2
- Q1: x = 10

- Q2: x = 2

- Q3: The codes prints "hello world" to the console every frame.

- Q4: ??? should be replaced with Monobehaviour

- Q5: These lines of code print "x = 10" to the console.

- Q6: The highlighted lines are arguments and parameters and they input for a method.

- Q7: The _playerTransform variable is instantiated but never used and Translate is being used on the Transform static class

- Q8: Transform.Translate should be replaced with _playerTransform.Translate.

### Activity 3

https://docs.google.com/document/d/1hYNliasaT5HCwedvTw8yrg4QrNS10bXhExGOnQw6uGg/edit?tab=t.0

## W2

### Activity 1
<img width="4032" height="3024" alt="daimage" src="https://github.com/user-attachments/assets/94605602-3c8f-42fe-b576-8559d56fcfaa" />

### Activity 2
[MG2 Commit](43aed4da89cfc50b0d6bccc929b7ef419108d000)

## W3

### Activity 0-2
Laura Liu

### Activity 3
<img width="4032" height="3024" alt="IMG_9925" src="https://github.com/user-attachments/assets/d5751f2c-72bd-49a9-a27d-a86597f9cba3" />

## W4

### Activity 0
Laura Lia, Alejandra Perez

### Activity 1
When you run the game while adding multiple Locator GameObjects, the additional GameObjects have their
script components destroyed so only one Locator exists in the scene.

### Activity 2
<img width="3060" height="2588" alt="IMG_9943" src="https://github.com/user-attachments/assets/51edc4fe-6aa3-461e-8ce8-3f67904ea98d" />

### Activity 3
[MG4 Commit](https://github.com/BilalPayton/HW4/commit/437fb2971d0178b3e06300d8766fc2fd295d2a0b)

## W5

### Activity 1
I would keep the design of the interfaces and abstract classes the same because the Item class does
not need to be used as a component the same way it's child class do and the interface is useful
because it helps label what actions can be done to a class.

### Activity 2
The ScriptableObjects (EnemyStats Class) represent the Model, the dialogue of the
enemies and ui class reperesent the view, the Player and Enemy represent the logic.

### Activity 3
Scenario 1:
Model: Data for note presses
View: Animation, Audio, Visuals, UI
Controller: GameController for keeping track of note presses

Enums for PlayingGameState and EndGameState

Singleton GameController


Scenario 2 Team Shooter:

Model: Game data such as character stats and weapon stats and inventory

View: Audio, Animations, UI

Controller: GameController to control the match timer, damaging players,
etc.

When characters are damaged, send an event to audio and visual effect
classes to play hit sounds and hit effects.

Singleton: GameController

Enums: GoodHealthState, CriticalHealthState, DeadState

Abstraction: Override abstract attack method for characters and
main parent character class abstract because we only need the child
classes for unique characters.

ScriptableObjects: Characters can be scriptable objects with different
stats such as name, health, attack, jump height, ultimate, etc.
Weapons can also be ScriptableObjects.

Scenario 3:
States for NPC's such as talkingState, walkingState, sleepingState, etc (enums)
GameController Singleton
Abstract NPC class to override NPC dialogue
Model: Crop and player and NPC data
View: Animations, Sprites, Audio
Controller: Crop growth rate
When opening a door, send an event for audio (door opening) and visual (door opening) classes
NPCS can also be ScriptableObjects

### Activity 4
Attendance: Bilal Payton, Bella Sloan, Laura Lia
[Final Project Proposal](https://docs.google.com/document/d/11w2xkRcvvsdrWrjTOsVOLnSm630WmjlCOwrMvn1rDKk/edit?tab=t.0)

## W6

### Activity 1
Gizmos: I think Gizmos is useful for debugging collision and velocity problems. This could be especially
helpful for our project to make sure the collision between the player and enemies works and it can invoke
events to other systems based on said collision.

Profiler: The profiler will be helpful for any optimization problems in our final project if any. If we have
any optimization problems we can use the profiler to check for spikes in frame rate and find in what methods
they occur in.

Breakpoints: Breakpoints will be useful in our final project for finding errors in our code that we may
not know where to look and this is very important because our final project will have a lot of code to
look through. Looking through all the code for the errors and then manually debugging them would take a 
while and using breakpoints helps save time.

### Activity 2
Attendance: Bilal Payton, Bella Sloan, Laura Liu

[Final Project Proposal](https://docs.google.com/document/d/11w2xkRcvvsdrWrjTOsVOLnSm630WmjlCOwrMvn1rDKk/edit?tab=t.0)