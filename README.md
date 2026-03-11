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

## W7

### Activity 1
Raycasting allows us to fire an arrow from an origin point in a certain direction. We can use this
to trigger NPC states depending on what the allow hits. For example, we can add a raycast that has an
origin point at an enemy to reperesent it's line of sight and if it hits the player, we can update their
state from a wandering state to a pursuing state where they will chase the player until they are out of
the arrows reach, in which the enemy will have it's state updated back to wandering.

### Activity 2
Bilal Payton, Bella Sloan, Laura Liu

### Activity 3

<img width="2360" height="1640" alt="Final Project Breakdown (The Goated)" src="https://github.com/user-attachments/assets/12b66b4b-0c2d-4b8d-b3fa-e8ce42137dfc" />


### Activity 4
[Trello Taskboard](https://trello.com/b/RdVdKvnk/gdim-32-final-project-the-goated)

### Activity 5
[Final Project Commit](https://github.com/BilalPayton/The-Goated-GDIM32-Final/commit/f0349303a553622efb1bb0fefeba4a2800d52459)

I imported placeholder background music that plays when the game starts. This will be switched out later
for scary music to match the horror theme our game has.

## W8

### Activity 1
Post-processing effects are shaders that affect the look of your entire screen. Post-processing effects
need to be compatible with your own rendering pipeline to work properly. Check IsGlobal on the Post-process
volume component. Set Post-processing GameObject to have the Post-processing layer.

### Activity 2
Attendance: Bilal Payton, Bella Sloan, Laura Liu

### Activity 3
Playtest Notes:
- Fix character sliding issue

- Mouse cursor sensitivity is too high, but like only on some people's laptops for some reason.

- Camera movement/player turning around is kinda janky and laggy --> missing Time.deltaTime so maybe that's the reason.

- Get cursor locked to screen

### Activity 4
My tasks are to allow the player to interact with items, add them to their inventory, and get in
2 unique animations in the game by the final check in.

### Activity 5
[Final Project Progress Commit](https://github.com/BilalPayton/The-Goated-GDIM32-Final/commit/640fceb657749397fe4412b19550349aead1da7d)
I started working on making items interactable. I've created a Beans GameObject/Prefab and also a
ScriptableObject script to store its data such as an items name, description, icon, etc. I've also
added a collider to the Beans prefab to try and get the onMouseOver method to work on it.

## W9

### Activity 1
Branching dialogue notes:
- Gives further dialogue options depending what the player chooses
- Branching dialogue options kept as data through ScriptableObjects becuase dialogue isn't always present in the scene
- Use dialogue controller for multiple npcs with different dialogue
- NPCs should have member variables for player dialogue choices and the npcs dialogue that can be tuned in the inspector
### Activity 2
Bilal Payton, Bella Sloan, Laura Liu
### Activity 3
Playtesting feedback: - player spin around...lock the y rotation or smth on the player prefab (already fixed). - Lower sensitivity (already fixed) - finish adding colliders to buildings (fixed) - add some dialogue ui that tells the player how to move around. - add sprint feature
### Activity 4
We are about halfway done with our project and think we can finish it by the deadline and this is where we are
supposed to be at this time. This conveys that our project scope scales well and gives us a reasonable amount
of time to complete it.
### Activity 5
[Final Project Commit](https://github.com/BilalPayton/The-Goated-GDIM32-Final/commit/27ab68ba08a6d5a394bb628a5cb062d3cfda5f11)
Originally I had two separate Zombie Male prefabs to showcase both the zombie idle and run animations for the check in, so I
combined both animations into one Zombie Male prefab after the playtesting for our game was finished. I also created a ScriptableObject
named NPCDialogue and created a few of them to start the branching dialogue process for our NPC Joe's lines, the player's options in how
they respond to his lines, and the replies Joe gives to the player depending which option they choose.

## W10

### Activity 1
Bilal Payton, Bella Sloan, Laura Liu
### Activity 2
Playtest feedback: 
- default speed too slow 
- sprint too fast 
- view is a bit too dark 
- when you walk too far away from the buildings the ui just dissapears
- mouse sensitivity still too high
### Activity 3
My task is to continue finishing the branching dialogue and implement the audio for the game.

We are getting close to finishing our project currently and we are supposed to be 
at this stage so this shows that our project scope is good.

### Activity 4
[Final Project Progress Commit](https://github.com/BilalPayton/The-Goated-GDIM32-Final/commit/66a278b2c72fecc3122dfa086da40e778fd8cc9f)

I fixed the problem of the player not being able to click on their response options after talking
to an NPC, and gave Joe some new dialogue that will start the quest to find his beans.