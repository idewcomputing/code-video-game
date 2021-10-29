# Top-Down Game

In this second practice, you're going to create a top-down game that shows an overhead view of the player. It will be a space shooter game, similar to [Asteroids](http://2600online.com/asteroids.php). This game will feature a nice balance of player skill, random chance, and increasing challenge. It will reinforce the basic concepts of using Phaser to create a game, plus show you some advanced features in Phaser.

Our game will be an update to the classic Asteroids that we'll call **Asteroids 2084**. Here's its premise:

> The year is 2084. The Mars colony is running out of water and needs to reach the icy moons orbiting Jupiter. You're a spaceship pilot sent on a scouting mission to clear a path to Jupiter through the asteroid belt. Asteroids threaten to collide with your ship from all directions. Your only option is to evade and destroy the asteroids before they destroy you.

In this practice, all the game assets (i.e., images and sounds) and **some** of the game code will be provided. Focus on two things: (1) becoming familiar with the new Phaser commands that will be introduced, and (2) applying the Phaser commands you've already seen.

![](../../.gitbook/assets/asteroids-title.png)

![](../../.gitbook/assets/asteroids-screen.jpg)

**PREVIEW VIDEO:** [Demo of Asteroids 2084](https://drive.google.com/open?id=0B8MTiM\_lFG9TVmwzX25HcFhkNW8)

## PREP STEPS

1. Complete the [Quick Setup](../quick-setup.md) for a new game.
2. Download assets zip file below, and extract the file contents, which will be a folder named **assets** that has two subfolders containing 12 images and 7 sounds. (To extract the file on a Windows computer, right-click on the downloaded zip file, and select _Extract All_. On a Mac, double-click on the downloaded zip file.)
3. Replace your new game assets folder with this **assets** folder with all the included files in the subfolders.
4. Test your Phaser game template by previewing the HTML file online. If everything's ready to go, you should see a **solid black box** (your blank game canvas) on your webpage.

{% file src="../../.gitbook/assets/asteroids assets.zip" %}

## CODING STEPS

This  game will be coded in 15 steps, with the last step being an extra credit challenge. Some steps will involve coding that's similar to things you did previously. However, most of the steps will also introduce and explain new Phaser features.

The steps are outlined below.

* Step 1: Add Player Sprite&#x20;
* Step 2: Add Player Input&#x20;
* Step 3: Add Physics and Player Movement&#x20;
* Step 4: Add Tilesprite Background&#x20;
* Step 5: Add Asteroids Group&#x20;
* Step 6: Add Player Collision with Asteroids&#x20;
* Step 7: Add Player Weapon&#x20;
* Step 8: Add Particle Effect to Asteroids&#x20;
* Step 9: Add Asteroid Spawning&#x20;
* Step 10: Add Score&#x20;
* Step 11: Add Player Shields (Health Bar)&#x20;
* Step 12: Add Player Lives&#x20;
* Step 13: Add Extra Life Reward&#x20;
* Step 14: Add Game Start and Game Over&#x20;
* Step 15: Add Enemy Ship (Extra Credit)
