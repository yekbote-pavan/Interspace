# Interspace
 A space journey: A free to play immersive experience through the vast cosmos

Requirements:
- Epic games launcher
- Unreal engine 4.27.2

How to play?
- Clone the repository or download the zip
- Run InfiniteMatrix.uproject
- Gl hf

# Details
Health:
- Each player has a max health of 100
- On hitting an obstacle (wall or enemy), health drops by 25
- Game ends when health reaches 0
- Displayed on the top left

Enemy:
- Enemies spawn at a rate of 33% per tunnel
- Enemies damage player by 25

Healthpack:
- Healthpacks spawn at a rate of 10% per tunnel
- Increase player health by 25

Blaster:
- Left click to shoot blaster
- Blaster kills enemies (increases score by 25)
- Blaster projectiles are deleted on impact with wall, healthpack or enemies

Score:
- Score increases by 25 for every successful escape
- Score increases by 25 on shooting an enemy

Gameplay:
- Game speed increases by 10% at every score interval of 200

Death:
- Restart option is displayed
- Score set to 0
- Health set to 100

Audio components:
- Gameplay music
- Sound for blaster projectile
- Sound for successfully escaping a wall
- Sound for picking up health pack
- Sound for taking damage
