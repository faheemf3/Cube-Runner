# Cube Runner Game

Cube Runner Game is a 3D endless-runner style arcade game built in Unity. The objective is to navigate a forward-moving player (cube) along a long track, avoiding various obstacles that spawn in your path. As you progress, your speed increases, testing your reflexes!

## How It Works

- **Obstacle Spawning:** The game dynamically spawns obstacles along the track randomly across different lanes. It supports multiple obstacle variations (e.g., different colored obstacles) that are selected at random.
- **Speed Progression:** Your base speed naturally increases slightly every time you cross 20 obstacles, and you can also select the "Next Level" button at the end to start at a faster base speed. 
- **Score System:** The game tracks how many obstacles you have successfully bypassed. Your goal is to reach the target total number of obstacles without crashing.
- **Game Over:** If you collide with any obstacle or fall off the edges of the track, you will crash and it will be Game Over. 

## How To Play (Controls)

The player continuously moves forward automatically. You only need to steer left and right to dodge obstacles. The game supports Keyboard, Mouse, and Touch controls out of the box using the new Unity Input System!

- **Keyboard:** Use the **A / D** keys or the **Left / Right Arrow** keys to steer left and right.
- **Mouse Drag:** Click and hold the **Left Mouse Button** and drag horizontally across the screen to smoothly steer your character. 
- **Touch Swipe:** On mobile devices, tap and swipe left or right across the screen to steer.

## UI & Interactions

- **Home Screen:** Shows welcome messages and allows you to read instructions or start playing.
- **In-Game HUD:** Displays your current live speed (m/s) and your progress (obstacles crossed vs. total). Pops up speed-boost notifications when crossing certain milestones.
- **Game Over / Level Complete:** If you crash, you'll see a game over screen specifying what you hit (or if you fell off). If you survive the entire track, you'll be greeted with a Level Complete screen where a Trophy animates!

---
*Built with Unity C#*
