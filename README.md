Download Link: https://assignmentchef.com/product/solved-cecs-277-project-4-star-wars-gui
<br>
<strong>Part A</strong>: Modify the code you wrote for Project 1 by incorporating the following design patterns into your program:

<ol>

 <li>Singleton

  <ol>

   <li>Item Generator</li>

   <li>Enemy Generator</li>

   <li>Map</li>

  </ol></li>

 <li>Prototype

  <ol>

   <li>Item – call the clone() function in ItemGenerator’s generateItem() function.</li>

  </ol></li>

 <li>Decorator

  <ol>

   <li>Enemy – The EnemyGenerator will no longer read from the file, instead create the following base classes: Rodian, Dathomiri, Twi’lek, Geonosian. Then create the decorators Fighter and Force User.  Attach the decorator titles to the name of the enemy (ie. Rodian Fighter or Rodian Force User).  Force User should implement the Force interface and its attack method will randomly call one of the force attacks.  Fighter should increase its maxHp by 1 when decorated, and Force User should increase its maxHp by 2 when decorated.</li>

  </ol></li>

 <li>Factory

  <ol>

   <li>EnemyGenerator – no longer reads from the file. Instead randomly generate one of the base enemies at the level of the hero.  If its level is greater than 1 randomly choose Fighter or Force User.  Then for each level greater than one, repeatedly decorate it with that type (ie. level 3 Rodian might be decorated with Fighter twice), this will cause it to gain additional maxHp and do an additional attack for each level.</li>

  </ol></li>

</ol>

<strong>Part B</strong>: Create a GUI for your Star Wars game:

Allow the user to walk through the map, just like the console version, but draw the map and the hero’s location to the screen.  Allow the user to use W, A, S, D (or Up, Left, Down, Right Arrow) keys to move around the map (implement either or both).

Write draw functions for your map and other classes that draw to the screen.

Create display areas for the player’s information and for action information that is updated as they move around the map (this replaces console output).

When an enemy attacks the user, make a fight and run away buttons, and if they have a Med Kit, have a third button to use it (use JButtons or clickable rectangles).  If they choose to fight, and they have a Holocron, allow them to choose between blaster and force attacks.  If they choose force attack, then have a button for each type of force attack.

If the user’s inventory is full, and they receive an item, then one needs to be dropped. Allow the user to select which item to drop by using the KeyListener for 1,2,3,4,5, or clicking on the item in their inventory (implement both).

Check for invalid input such as moving around the map while fighting or dropping items Other functionality should be the same as it was before.

Bonus points for drawing images for each of the different items and enemies.  You may modify the item text file to include the file names of each of the images.

Example screenshots are given below, but yours does not have to match exactly.





