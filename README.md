# Welcome to the Maze of Waze!

Navigation game in the space

play with your aliens and collect stars as much as possible!





# Welcome:

![Welcome](http://www.up2me.co.il/imgs/67178178.png)

 
# Introduction:

The maze of waze, is a game locate in the space, that you have to collect stars as much as possible to got the highest score.

# Description:

Location: Space

What your character: Aliens

What do you have to do: collect stars as much as possible

What the purpose: to get the highest grade (score) by collecting stars.

Example for Scenario 1:

![Scenario1](http://www.up2me.co.il/imgs/1172321.jpeg)

Example for Scenario 11:

![Scenario11](http://www.up2me.co.il/imgs/98026818.jpeg)



# GameClient:

**SimpleGameClient:** 

The Class SimpleGameClient represents a simple exmaple for using the GameServer API.

**MyGameGUI:**

The Class MyGameGUI, containing the main using of the GameServer API, that including the Manual gaming option,

and a link to the Auto gaming option (that inside the class MyGameAlgo).

the class using Thread, and including a constructors, and functions as startGame, run  (Thread Override), updateRobots, 

updateFruits, placeRobots, findRange, openWindow, moveRobots, findNode, printGraph, printFruit, printRobots,

numOfRobs, Getters, Setters and finishGame.

**MyGameAlgo:** 

The class MyGameAlgo is the Auto option class of the game.

the class including functions as startGame, run (Thread Override), placeRobots, moveRobots, setMyGG and getNextNode.

this class uses MyGameGUI class as basis.


**KML_Logger:**

KML is a file format used to display geographic data in an Earth browser such as Google Earth.

You can create KML files to pinpoint locations and add image overlays.

we make an option to make that file from the game, and locate the game in Google Earth.

KML is an international standard maintained by the Open Geospatial Consortium, Inc.







# Elements:

**RobotInterface:**

The interface RobotInterface, represent a character that init from Json file, in a String format.

the interface support at Robot list with ArrayList.

**Robot:**

The class Robot represent a character in a alien visible, call robot.

The class implements the Interface, and realize all the functions.

in addition, Robot class have a constructor, update function, getters and setters.

**FruitInterface:**

The interface FruitInterface, represent an object that init from Json file, in a String format.

the interface support at Fruit list with ArrayList, and Getter for the Edge that the fruit on it.

**Fruit:**

The class Fruit represent an object in a star visible, call fruit.

The class implements the Interface, and realize all the functions.

in addition, Fruit class have a constructors, update function, isOnEdge function, getters and setters.





* we used STtdDraw and a liitle bit JFrame to implement the GUI of the Game

**More details about classes and interfaces of the project can be found on Wiki**

We hope you enjoy !

![GameOver](http://www.up2me.co.il/imgs/70056305.png)
