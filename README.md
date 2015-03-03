Kick-Spot
=========

An easy-understanding sample for learning Property Animation&ConcurrentLinkedQueue and Queue of Android

APP Summary：

The Kick Spot game tests a user’s reflexes by requiring the user to touch moving spots before
they disappear. The spots shrink as they move, making them harder to touch.
The game begins on level one, and the user reaches each higher level by touching 10 spots.
The higher the level, the faster the spots move—making the game increasingly challenging.
 When the user touches a spot, the app makes a popping sound and the spot disappears. 
Points are awarded for each touched spot (10 times the current level). Accuracy is
important—any touch that isn’t on a spot decreases the score by 15 times the current level.
The user begins the game with three additional lives, which are displayed in the bottom-
left corner of the app. If a spot disappears before the user touches it, a flushing sound plays
and the user loses a life. The user gains a life for each new level reached, up to a maximum
of seven lives. When no additional lives remain and a spot’s animation ends without the spot being touched, the game ends

Key Technology Overview:

•Android 3.x and Property Animation
references:android-developers.blogspot.com/2011/02/animation-in-honeycomb.html

•ConcurrentLinkedQueue and Queue
We use the ConcurrentLinkedQueue class (from package java.util.concurrent) and the Queue
interface to maintain thread-safe lists of objects that can be accessed from multiple threads of execution in parallel.



