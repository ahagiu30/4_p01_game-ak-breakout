# Project 01 For NeXT CS
### Class Period: 4
### Name0: Anika Das
### Name1: Zariya Kardar
---


Your mission is to recreate one of these two classic arcade games:
- Breakout/Arkanoid [demo 0](https://elgoog.im/breakout/)  [demo 1](https://www.crazygames.com/game/atari-breakout)
- Space Invaders [demo 0](https://elgoog.im/space-invaders/) [demo 1](https://www.crazygames.com/game/space-invaders)

This project will be completed in phases. The first phase will be to work on this document. Use makrdown formatting. For more markdown help [click here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) or [here](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)


---

## Phase 0: Game Selection, Analysis & Plan

#### Selected Game: breakout

### Necessary Features
What are the core features that your game should have? These should be things that __must__ be implemented in order to make the game playable, not extra features that could be added to make the game more fun to play.

The game needs a paddle that can be moved by the player's mouse, a ball that bounces within the screen

### Extra Features
What are some features that are not essential to gameplay, but you would like to see (provided you have time after completing the necessary features.

3 lives until the game/score resets, changes color based on what block it hits, 


### Controls
How will your game be controlled? If the mouse will be used, explain how. List all keyboard commands as well.

Keyboard Commands:
- reset game when SPACEBAR (' ') is pressed

Mouse Conrol:
- Mouse movement: the center of the paddle follows mouseX
- Mouse pressed:


### Classes
What classes will you be creating for this project? Include the instance variables and methods that you believe you will need. You will be required to create at least 2 different classes. If you are going to use classes similar to those we've made for previous assingments, you will have to add new features to them.

CLASS Paddle
- Instance variables:
  - x, y, rwidth, rheight
- METHODS
  - display, move, bounceBack?

CLASS Ball
- Instance variables:
  - cx, cy, xvelocity, yvelocity, radius
- METHODS
  - constructor, display, ball, reset, move, changeSpeed

CLASS Block
- Instance variables:
  - x, y, rwidth, rheight
- METHODS
  - array, random, display
