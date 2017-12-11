# Traceball-Project-1
## Core Requirements:
#### The core requirements are to have two different characters, one must be a none playing character which is controlled by the computer and one character controlled by the user. This NPC follows the users location and moves across the screen towards them, the user can use its character to move away from the NPC and once the NPC has collided with the users character then a life is lost. The game ends when 3 lives have been lost. The coding will be all in Javascript and the platform will be Google Chrome.

## Game Description:

#### The game is about surviving as long as possible. There is a chaser and a player, the player must use the mouse to move away from the chaser who will try and collide with the player position. Once the player has collided 3 times the game ends.

## User Stories:

#### 1. As a user I would like to play the game in my browser (cross platform)
#### 2. As a user I would like to play the game multiple times (New game button)
#### 3. As a user I would like to have my character move in a 2 dimensional enviroment
#### 4. As a user I would like to have a visual representation of the player and NPC
#### 5. As a user I should get feedback when there is a collision between the NPC and player
#### 6. As a user I would like to know when I have won/lost the game
#### 7. As a user I  would like to change the difficulty of the game to challenge myself

## Flow Chart:
![flowchart](https://github.com/kap14275819/Traceball-Project-1/blob/master/Traceball%20flowchart.png)

## Product Backlog:
### High Level Function Requirements:

#### Create Canvas(550 x 350pixels)
#### Create 2 dimensional character (Circle)
#### Create 2 dimensional NPC (Circle)
#### User mouse movement moves character
#### Have NPC move to player position
#### Character stays within Canvas
#### Collision detection and display 
#### 3 lives
#### Start and stop game

### High Level Non-Functional Requirements:

#### Canvas Colour 
#### Character and NPC shape
#### Player and NPC colour
#### Canvas size

## Sprint Backlog:

#### I would like to play the game in my browser (cross platform)
#### I would like to play the game multiple times (New game button)
#### I would like to have my character move in a 2 dimensional enviroment
#### I would like to have a visual representation of the player and NPC
#### I should get feedback when there is a collision between the NPC and player
#### I would like to know when I have won/lost the game
#### I  would like to change the difficulty of the game to challenge myself

## Design Documentation:
### Process of Implementation

#### The first item that was created was the HTML page which will be the platform for the game to run on. Then the canvas was made so that there will be a playable area for both the NPC and player. Next was the mouse to be tracked on the screen to the canvas, when tracked the mouse was given a 2Dimensional image so that it looks more like a character. Once that was done the NPC was then created with a similar shape but different colour. This NPC was then given the position of the player so that it may track them and chase down the character. Finally when the NPC is following the users character its then was given a dectection so that when the two collide it will detect that they have hit and then will display that it has collided. The user character is then given 3 lives for when it has collided with the NPC.

## Gantt Chart:
![ganttchart](https://github.com/kap14275819/Traceball-Project-1/blob/master/Gantt%20chart%20Project%201.png)
### IDE used and Features:

#### There was no Integrated Development Environment that was used but instead a text editor was used which was notepad. Even though notepad is a has no features which could have helped during the coding it still provided an area to write code and to save the file.

### Debugging Process:

#### The IDE did not have any features for debugging so it would have either had to be done manually by scrolling through the code to find the problem and fix it or you would have to us the console from the platform was used which was Google Chrome.

### Coding Standards:
#### While writing my code, indenting was used more often than spacing mainly because it saves time instead of repeatedly pressing or holding the space button.

## Research:
#### The types of places that i used for research was usually forums such as 'stackoverflow' which helped on some parts of fixing code but also i used websites such as 'w3schools' which is a coding website and shows multiple different types of coding examples which helped to understand how some of the pieces of code worked. Other forums were also used that are not that known to look through code snippets which helped throughout the process.

## Evalution and Teamwork:
#### Overall the game was quite a hard challenge to complete even when i had a shorter amount of time, but still ended up quite well. Some parts were simple but after those tasks were completed the harder ones made it more challenging. In my opinion i think it was a good project and quite entertaining at the end of it as it was finalised but the most difficult part was to get the NPC to follow the users character. This work was managed by myself as it was an individual project without any teamwork. The research, coding and planning all was personally done which was quite good as it shows that i was able to complete this task without any help needed. The research and planning took its time but ended up all well in the end.

## Relationship between algorithm and code:
#### Since the program had been implemented as an algorithm then the best paradigm would be procedural. This is because the program does the process in computational steps, which is just like an algorithm. This is why the procedural paradigm is similar to the program.

