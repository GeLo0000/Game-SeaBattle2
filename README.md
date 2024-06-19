# Game Sea Battle 2

---

## Project Overview

This project was created to develop skills in Object-Oriented Programming (OOP), specifically in using 
design patterns, inheritance, and polymorphism.

**Sea Battle 2** is a game where the player competes against a bot (computer) under unconventional naval 
battle rules. This game features different grid sizes, varying levels of bot difficulty, random or 
manual ship placement, and most importantly, three different types of ships with unique functions.

---

## Technologies Used

- **Programming Language**: C++

---

## Game Rules

Each player has a grid where ships and mines are placed. Players take turns with the computer to 
fire at the opponent's grid, trying to sink the enemy fleet. When a player hits an enemy ship, 
they get another turn to shoot. If a player hits an opponent's mine, the corresponding cell on 
their grid is destroyed. The game continues until one player has no ships left.

---

## Menu

**Grid Size Selection**

**Ship Location Selection**

**Bot Difficulty Selection**

![Menu](README_media/menu.png)

---

## Ships

There are three types of ships, each with distinct markings and actions upon destruction. 
Each player has one four-deck fuel ship, one four-deck flagship, and several 
regular ships (the number of which depends on the grid size chosen by the user).

### Regular Ship

Marking: **O**

A regular ship operates under normal rules and has no special actions upon destruction.

### Fuel Ship

Marking: **F**

Upon destruction, the fuel ship creates a double damage zone around itself. If other ships' decks 
are within this zone, those decks are destroyed as well.

### Flagship

Marking: **C**

The flagship acts as a command center for all other ships. When it is destroyed, its final command 
to the fleet is to fire three consecutive shots at the opponent's grid. So, when your flagship is 
destroyed, you can take three shots at the opponent's grid.

---

## Bot Difficulty Levels

**First level** - The bot always chooses attack cells randomly.

**Second level** - The bot chooses cells randomly but tries to determine and destroy the ship's 
orientation (horizontal or vertical) after the first hit.

**Third level** - The bot operates like the second level but also considers all hits from mines 
and fuel ships, attempting to understand and destroy their positions.

---

## Gameplay

Example of gameplay in Game Sea Battle 2:

![Gameplay](README_media/gameplay.gif)

---

## Conclusion

Game Sea Battle 2 has been a significant step in enhancing my understanding and application of 
OOP principles. Through this project, I have gained valuable experience in using design patterns, 
inheritance, and polymorphism. Additionally, developing the game has improved my problem-solving 
skills and my ability to create complex algorithms. This project has prepared me for tackling more 
sophisticated and challenging projects in the future.
