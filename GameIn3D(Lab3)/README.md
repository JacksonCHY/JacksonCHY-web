## A Wondering Ball in City, a Unity 3D tour map. 

### What about this game… 

![alt text][logo]

[logo]:https://github.com/JacksonCHY/JacksonCHY-web/blob/master/GameIn3D(Lab3)/excerpt1.png"
###### Excerpt 1. The Interface

![alt text](https://github.com/JacksonCHY/JacksonCHY-web/blob/master/Interactive%20Mapping%20(Lab%202)/Excerpt.png "Excerpt Of My Map")
#### Reflective Analysis: 
##### Who did I design the guiding map for?
Have you noticed the Sci-Fi movie scene? In this assignment, I intended to construct a guide touring map for future city/cities. Imagine the “wondering ball” as the player in the map that brings you to check out what is interesting about the place. The floating “cubes” would then represent a landmark or an attraction, and when our player hit it may stop and a pop-up window may show with a brief description. I also construct walls around to illustrate the city limits. A counter on the top of the screen shows the number of points that the player has visited. 
##### In term of accomplishment & limitations?
Although I’m a beginner in the Mapbox SDK and Unity which kind of limits my hand to realizing some crazy ideas in mind. In this assignment, I use this opportunity to learn and try out new features in the software as much as possible. To give a third-person view of the players, I placed the main camera with the “wondering ball” object and manipulate the camera angle, so the scene is enabled to follow the player in the middle of the screen. For the background design, I modified the Mapbox base map style as well as the building into transparent structures. Therefore, the buildings will not hinder map users view but also set a futuristic setting of the city. On the other hand, player control script and the “immediate position with Location Provider” script makes our object following the path of streets. To a great extent, they prevent the player from “crush” into buildings. 
However, the guiding map has few other issues left behind unsolved. Even though I create the “cubes” and “walls” as markers, the collider C# code failed to work. Thus the ball can still penetrate through the structures and the cube markers did not vanish when the player went through them. Also, the SDK plug-in may not support pop-up windows which reduce the interactivity. I tried to put down the menu, direction control, and a droid button by downloading packages from the Asset Store. Yet coding errors and unmatched version (some tutorials required 1.4v or lower version) became my primary obstacle to building these interesting gadgets. 

#### Collaborations and reliance on other resources
As the first game I ever create with no previous experiences in Unity 3D, it would be very challenging without reference to online sources and inputs of others. To set up the project, the Youtube tutorial series [“Build a Unity 3D game”]( https://www.youtube.com/watch?v=RhG1kfDBhgM) offered by the Mapbox: allows me to learn about styling the base map, put up the UI, Game Managers, as well as placing the player on the map. It also briefly touches on the interface design and how to create buttons, images and texts on the game. My classmate Carolina recommended this tutorial from the Unity which I benefit most from the [Roll-a-ball Tutorial]( https://unity3d.com/learn/tutorials/s/roll-ball-tutorial). The video involves writing player control scripts and camera manipulation. I attempt to common game features such as direction control and “droids” button through watching this clip [“How to create mobile joystick in Unity 2018”]( https://www.youtube.com/watch?v=8-X3BmvtXT0). 

##### Map Critique
Iris was invited to be my map critics for this exercise. She was keen on the overall visualization and the count function embedded. In her opinion, despite technical constraint, the camera is better to put in a higher position such as a moving air balloon to tour around the city in a god’s view. Changing the buildings texture into the “realistic” setting may derive a more reality cityscape. 

