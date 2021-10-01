# TheUltraGame
2d platforming shooter written in Python using the PyGame library.

Created with a partner, the goal of the game is to defeat all the enemies in each of the four levels without dying. The arrow keys are used for movement and space is to shoot.

There are four types of enemies:
- Zero
  - Chases the player and can jump on platforms.
- Goomba
  - Walks back and forth on the platform which it spawned.
- Boo
  - Floats toward the player. Stops moving when the player is near by and looks at it.
- Metal Slug Missile Shooter
  - Remains stationary and fires ranged attacks at constant intervals. Will randomly fire an explosive attack that does extra damage.

There are no more than 5 enemies on screen at any given time, and when one of them dies another will spawn until all enemies for that level are defeated. Health potions will also spawn randomly which the player can collect to replenish a small amount of health.
