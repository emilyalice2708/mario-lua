# Mario

## About

Mario game built using Lua and Love for the Game Track of the Harvard Online CS50 Intro to Computer Science course. This project is an addition to the distribution code provided by the course.

## Course Objectives and Specification

- Read and understand all of the Mario source code from the last track lesson.
- Add a pyramid of blocks to the generated level.
- Add a flag at the end of the level that either loads a new level or simply displays a victory message to the screen.

Add a pyramid of blocks to the generated level. Taking into consideration the column-based generation we discussed in the track, find a way to generate a Mario-style pyramid like the below, placed directly atop the ground (ASCII flag to the right shown as well):
```
      #      ~
     ##      |
    ###      |
   ####      |
 ###############
 ```
You may choose to alter the pyramid such that it is symmetrical, but avoid a pyramid going the opposite direction, for Mario therefore won’t be able to climb it! Also be careful to avoid starting the generation too close to the end of the level :)
Add a flag at the end of the level that either loads a new level or simply displays a victory message to the screen. Also tied to generation, this time take the flag and flagpole sprites included in the distro’s sprite sheet and create a flagpole at the end of the level that, upon Mario’s collision, triggers either a victory message or a reloading of a brand new procedurally generated level.
