#Shooter
##Date: 04/10/2013
##Version: v1.0.0
##Author(s): Michael Cummings
##URL: http://michaelcummings.net/wingamekit_shooter

----------
###Description
A Starter Kit for Windows, and Windows Phone using [Construct 2][0] from Scirra

![alt text][1]

**Shooter** is a simple shooter app template, it is a side scroller with the enemies appearing from the right and attacking the player on the left. The player can move and shoot down the enemies to gain score. Health is lost for each enemy not destroyed and for each collision with an enemy. The game ends when the player runs out of lives.

###Features
 - Splash Screen
 - Movement
 - Parallax Background
 - Enemy Spawn
 - Health / Lives

###Requirements
 - Constuct 2 from Scirra
 - Windows 8 or later
 - Visual Studio 2012 or later
 - Windows Phone 8 Developer Tools ( for Windows Phone Games )

###Setup
To modify the game open the .capx file in Construct 2, and load the 'CustomizeGameHere' Event Sheet. Inside the Event Sheet you can modify the following configuration values :

 - HEALTH\_LOST\_PER\_COLLISION\_WITH\_ENEMY : _The Number of Health Points lost when Player collides with an Enemy_
 - HEALTH\_LOST\_PER\_MISSED\_ENEMY : _The Number of Health Points lost when Player fails to shoot down an Enemy_
 - SCORE\_EARNED\_PER\_ENEMY\_SHOT : _The number of Score Points gained when Player shoots down an Enemy_
 - PlayerMovementSpeed : _How fast does the Player move_
 - MaxLives : _Initial number of Lives player starts with_
 - MaxHealth : _Initial health for each players ship_
 - MaxFireRate : _Time delay between player shots_

You can also add additional features to the game to differentiate it from others made from this template:
 - Add additional levels
 - Add different enemies
 - Add enemies with different power levels
 - Add Power-Ups for the player

  [0]: http://scirra.com "Construct 2 from Scirra"
  [1]: https://github.com/wingamekits/Shooter/blob/master/Screenshot.png
