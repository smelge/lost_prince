# The Lost Prince

HOW TO PLAY!
============
* Download from Github
* Unzip to a folder and navigate to it in Terminal
* npm install
* npm start
* In your browser, go to localhost:3000
* When you die, refresh the page. It doesn't have a reset yet!

========================================================================

This is a Codeclan group project by:
  https://github.com/Jen-Jen91
  https://github.com/Jordanraitt
  https://github.com/n00dl3nate
  https://github.com/smelge/
 
 The original repository with commits and code breakdown is here:
 https://github.com/n00dl3nate/Pro_Z
  
 The brief was to produce a game in Javascript over the course of a week. The final product was designed as a simple RPG. 
 The player starts with 3 directions to travel in. Each movement randomly generates a room that can contain a monster, 
 health or attack upgrade. After a certain number of moves, the player wins. Monsters are generated from a Dungeons and 
 Dragons API.

 We used Bootstrap to style the frontend.
 
 =======================================================================
17-1-19 
=======

Bugfixes
========
* Player took damage instantly when attacked by enemies instead of when hit
* Enemy Healthbars would use HP as percentage of Healthbar. e.g. Starts at 100%, when updated would drop to 15% if HP was 15
* Player death would be instant with no time to see what killed you. Added delay for Death Screen.

Improvements
============
* Removed files that were doing nothing
* Removed old commented out code
* Cleaned up some functions
