# space_invaders_1.0

This is a space invader clone is a tutorial project found in Python Crash Course 3rd edition by E. Matthes [1]. The purpose of following this tutorial was to familiarize myself with how to structure a python project and learn abit about pygame.

# Features I added to the project

I added poorly made sound effects for bullets being fired from spaceship and explosion when alien is hit by bullet.

# Rules to the game

- Right and Left arrow keys are used to move the spaceship right and left respectively.
- Space bar is used to fire bullets.
- Only 3 bullets can be fired at a given time.
- The ship has 3 lives (shown in the left top corner).
- The fleet of aliens moves left to right and right to left.
- When the fleet swiches direction it moves down closer to the ship.
- A ship is lost if the fleet hits the ground or comes in contact with the ship.
- Once all 3 are lost the game is over
- The score is displayed on the right top corner.
- Below the score is the level which gets incremented when the fleet is eliminated.
- At each new level the fleet and ship moves faster to increase difficulty
- The highest score is displayed at the top in the middle.

# How to play the game

(1) run in terminal at root of project: python alien_invasion.py or python3 alien_invasion.py 

(2) Press the play button
<img width="1198" height="828" alt="Screen Shot 2025-11-12 at 8 45 27 PM" src="https://github.com/user-attachments/assets/d7f14782-4ddf-4602-94be-39fb7697650b" />

# References

[1] E. Matthes, Python Crash Course, 3rd ed., San Francisco, CA, USA: No Starch Press, 2023.
