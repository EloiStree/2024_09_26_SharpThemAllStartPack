

# Sharp Them All Starter Pack

You have RC Toys (air, water, ground), and using C#, your goal is to catch all the checkpoints.  
There are two challenge modes: **Speed** and **Survival**.  
Think carefully about your code.

This workshop is designed for the **C# Week** at Charleroi Street AR.  
The goal is to learn C# in Unity without focusing on learning Unity3D itself.  
Don’t try to skip steps—focus on the C# concepts.  
- GitHub: https://github.com/EloiStree/HelloSharpForUnity3D/issues?q=Keyword%3A

If this is your first time coding, feel free to use Scratch to help you better understand the basics:  
- GitHub: https://github.com/EloiStree/HelloScratchToUnity/issues?q=Keyword%3A

This game is designed to help you learn coding and Unity3D through interactive gameplay.  
In future versions of the Integer Games concept, the game will also be playable using LUA and online multiplayer features.

We’ve previously spent two weeks discovering **Gaming** and **AR**.  
This game is set at **Quai 10**, featuring boats and helicopters as part of the workshop.

---

## Speed Challenge

### Speed Level 0
The checkpoints are fixed on the map. Catch them all.

### Speed Level 1
You’ve caught the fixed points and learned some coding.  
Now, the checkpoints will spawn at random locations.

---

## Survival Challenge

### Survival Level 0
Add some input to your code to move the RC drone. Keep it alive for as long as possible.

### Survival Level 1
When you lose a drone, the difficulty increases.  
Try coding a solution to make all drones survive even when you’re not controlling them.

### Survival Level 2
Every few seconds, a new projectile is added to the game.  
Survive as long as possible while dodging the increasing number of projectiles.

### Survival Level 3
The game can support up to 16,500 projectiles.  
Your `foreach` loop and code will start to take time to process.  
At an average of 45 frames per second, the game will trigger a **Game Over**.


### Survival Level: Intermediate
You’ve reached 16,000 projectiles, and all of my façade code is disabled.  
(Note: This is not automated in this workshop—you’ll have to disable it manually.)  
Now, it’s your turn to implement what I’ve done for you, using the **Job System**.

The only information being sent to you now is:
- The position of your drones.
- The position of the checkpoint.
- The appearance and disappearance events of the projectiles.

The only information you can send is:
- An integer to control your drone.
- The integer command for this game: **00998877661**
  - `00`: Index of the drone.
  - `99`: Joystick left horizontal.
  - `88`: Joystick left vertical.
  - `77`: Joystick right horizontal.
  - `66`: Joystick right vertical.
  - `1`: Generic action (not used in this game), such as Fire, Interact, or Kill Switch on/off.


### Survival Level: Advanced
Okay, the game is too easy for you! Let’s see how many projectiles your GPU can handle and how your code performs under pressure.  
This is now a personal challenge—I'll keep increasing the number of projectiles, and you must try to survive.

If you're up for the challenge, ping me on Discord with the message: **"Too easy, we need more!"**  
![image](https://github.com/user-attachments/assets/65b11142-95e5-41f3-a80c-b53611834b03)  
Contact: https://github.com/EloiStree



## Final Goal

We have one week to learn as much as we can about C# to move and survive in this game.  
Feel free to add some human interface elements (joystick, keyboard, etc.)—it makes the game more fun.

However, the difficulty level of the game will be adjusted to not go easy on you if you lose some drones.  
So, focus on writing code that works without manual input.

The platform for the final test of the workshop is the **Quest 3/3s**.  
If your code works on your phone, it will run on the Quest.

May the code be with you all.

Have fun flying at **Quai 10**!





-------------------------

 Code Package to build this project:
 - https://github.com/EloiStree/2024_09_26_SharpThemAllStartPack/issues/2
