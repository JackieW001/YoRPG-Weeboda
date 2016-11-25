## YoRPG
   Swashbucking RPG game through the comfort of your terminal. Defeat the evil Smaug Monsters :japanese ogre: and free the land! Onward Young Adventurer!

# Cool Features
1. Choose your Difficulty Level
2. 5 different characters to choose from!
3. HP, attack rating, defense, strength, and name attributes for each character

# Code Structuring
  All code was written in Java. 
  YoRPG.java is the driver file where the magic happens, so if you're interested in the innerworkings of the RPG be sure to check the file out!  
  An umbrella Character class holds all attributes and methods for each specific character and each character (Warrior, Mage, etc.) inherits all atributes and metods from the Character class. Abstract methods in the Character class, such as specialize(), normalize(), and about() were overwritten in the subclasses of Character
  Monster was created as a separate class unrelated to the Character class. The Monster class includes all the same attributes as the Character class except the name attribute and all the same methods as the Character class except the specialize() and normalize() methods.

# How do I play this super awesome game?
1. Clone repo
2. "cd" into the repo through the terminal
3. Compile the YoRPG Java file by typing into the command line:
   javac YoRPG.java
4. Run the Java file by typing:
   java YoRPG
5. Have fun!
