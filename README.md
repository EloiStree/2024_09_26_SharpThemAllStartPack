

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









------------------



Current Packages to build the project.
``` json

    "be.elab.3dbenchy": "https://github.com/EloiStree/2024_09_14_3DBenchy.git",
    "be.elab.bedroomfromsketchfab": "https://github.com/EloiStree/2024_08_16_BedroomFromSketchab.git",
    "be.elab.besttiming": "https://github.com/EloiStree/2024_09_06_BestTimingScore.git",
    "be.elab.boattoy": "https://github.com/EloiStree/2023_09_15_KidToyBoatModeCode.git",
    "be.elab.charleroifort": "https://github.com/EloiStree/2024_09_25_Charleroi1666.git",
    "be.elab.developernote": "https://github.com/EloiStree/2024_08_09_DeveloperNote.git",
    "be.elab.dualscreenstick": "https://github.com/EloiStree/2023_01_28_ScreenDualJoystick.git",
    "be.elab.elabtoyrc": "https://github.com/EloiStree/2024_09_28_eLabToysRC.git",
    "be.elab.flyingisland": "https://github.com/EloiStree/2024_09_10_FlyingIsland.git",
    "be.elab.fpvtoy": "https://github.com/EloiStree/2024_10_02_KidToyFpvDronerModeCode.git",
    "be.elab.hellocopter": "https://github.com/EloiStree/2024_09_10_HelicopterMove.git",
    "be.elab.ilegamenid": "https://github.com/EloiStree/2024_09_11_FloatingIslandNidGaming.git",
    "be.elab.irctoy": "https://github.com/EloiStree/2023_09_15_IToyControllerRC.git",
    "be.elab.netshortspace": "https://github.com/EloiStree/2024_10_02_32767MMPlayZone.git",
    "be.elab.patounerace": "https://github.com/EloiStree/2024_10_02_PatouneRace.git",
    "be.elab.quaiboatnidar": "https://github.com/EloiStree/2024_09_23_Quai10Boat.git",
    "be.elab.quaimeasure": "https://github.com/EloiStree/2024_09_22_Quai10Mesh.git",
    "be.elab.quickfollowit": "https://github.com/EloiStree/2024_09_16_QuickFollowIt.git",
    "be.elab.quickgitutility": "https://github.com/EloiStree/2019_07_21_QuickGitUtility.git",
    "be.elab.renderscreenxr": "https://github.com/EloiStree/2024_09_17_DroneRenderScreenXR.git",
    "be.elab.sketchfabdronemesh": "https://github.com/EloiStree/2024_08_05_SketchFabDroneMesh.git",
    "be.elab.skidtoycar": "https://github.com/EloiStree/2023_11_01_KidToyCarSkidSteeringCode.git",
    "be.elab.skyriding": "https://github.com/EloiStree/2024_09_03_SkyRidingPath.git",
    "be.elab.startpackboatoy": "https://github.com/EloiStree/2023_09_16_StartPackBoatToy.git",
    "be.elab.startpackquaiscan": "https://github.com/EloiStree/2024_09_25_StartPackQuai1666.git",
    "be.elab.submarinetoyrc": "https://github.com/EloiStree/2024_09_30_KidToySubmarineModeCode.git",
    "be.elab.tellotoy": "https://github.com/EloiStree/2023_02_19_KidToyDroneTelloModeCode.git",
    "be.elab.tickcollection": "https://github.com/EloiStree/2024_08_05_TickCollection.git",
    "be.elab.uvdrawabledrones": "https://github.com/EloiStree/2024_08_05_UvDrawableDrones.git",
    "com.unity.inputsystem": "1.7.0",
    "com.unity.probuilder": "5.2.3",



    "be.elab.developernote": "https://github.com/EloiStree/2024_08_09_DeveloperNote.git",
    "be.elab.livingcodeattribute": "https://github.com/EloiStree/2024_08_18_LivingCodeGUID.git",
    "be.elab.nprojectile": "https://github.com/EloiStree/2024_08_14_NetworkableAsteroidsGame.git",
    "be.elab.snam16k": "https://github.com/EloiStree/2024_04_16_SNAM16K.git",
    "be.elab.stayaliveexercice": "https://github.com/EloiStree/2024_08_15_StayAliveExercice.git",
    "be.elab.tellotoy": "https://github.com/EloiStree/2023_02_19_KidToyDroneTelloModeCode.git",
    "be.elab.tickcollection": "https://github.com/EloiStree/2024_08_05_TickCollection.git",
    "be.elab.watchexecutetime": "https://github.com/EloiStree/2024_04_18_WatchExecuteTime.git",
    "be.elab.watchtimelayersexecution": "https://github.com/EloiStree/2024_08_18_WatchTimeLayersExecution.git",
    "be.elab.capsulecollisionutility": "https://github.com/EloiStree/2021_08_19_FTLBullets_CapsuleCollisionWithMathAndJob.git",
   

```










