# MG3
## Devlog
### 1
The default value for a float is "0.0", an int is "0", a bool is "false", and a string is "null".
### 2
Unity calls the "Update()" method automatically once per frame while the GameObject is active and the component is enabled. We do not need to call it manually.
### 3
The "TimerText" class uses the Timer to keep track of the game time. In "Start()", it calls "BeginTimer()" to set the starting time. In "Update()", it gets the remaining time and updates the timer text on the screen. It also checks whether the timer has finished and calls "GameOver()" when the time runs out.

## Open-Source assets
- [Cat fighter spritesheet](https://opengameart.org/content/cat-fighter-sprite-sheet)
- [Food sprites](https://rcpstd.itch.io/pixel-food-pack)
