 # Project Overview

The game is a space invaders clone but with updated textures. The theme is Kanye West vs Adidas and Skete.

## Enemy types
The enemies are Skete, Adidas Executive and Kid Cudi. They will have different health and will be harder to kill. They will also do more damage depending on the enemy type.
### Enemy Images
Skete
![Enemy 3](Enemy/Enemy%203.jpg)

Adidas Executive
![Enemy 1](Enemy/Enemy%201.jpg)

Kid Cudi
![Enemy 2](Enemy/564901_v9_bb.jpg)

## New Gameplay
There will be barriers added like the real space invaders that makes it harder to be killed but they will have health and eventually can get destroyed. There will also be lives and if you run out of all the lives you will lose the game. There will also be something you have to protect at the bottom.


# Behaviour - User Journey
```mermaid
journey
  title User Journey
    section Main Menu
        Press Options button: 5: player
        Turn on Automatic firing (Optional): 5: player
        Press Start Game: 5: player
    section Main Game
        Move Around: 5: player
        Shoot enemies: 5: player
    section If timer runs out
        Send to Lose Screen: 5: ui
        Click retry Button: 5: player
    section If Player loses health
        remove heart from live counter: 5: ui
        Send to Lose Screen: 5: ui
        Click Retry: 5: player
    section If Vault destroyed
    send to lose screen: 5: ui
    Click Retry: 5: player

```
# Planning Diagram - Project Plan

```mermaid
gantt
    title Kanye Vs Skete Project Plan
    dateFormat DD-MM-YY
    axisFormat %d-%B
    tickInterval 1week

    section Holidays
    Schools Holidays: 09-04-23, 22-04-23

    section Design
    Project Overview:05-04-23, 1d
    Project Plan: 05-04-23, 24-04-23


    Section Implementation
    UI:01-05-23, 04-06-23
    Barriers:14-05-23, 4d
    Testing:05-04-23, 07-06-23
    Lives:26-04-23, 1d
    The Vault:08-05-23, 3d
```