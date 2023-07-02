# Game Programmer Generalist
### I am a generalist game progammer looking forward to start my professional career as technical artist!
### Take a look at some of my work ^^

# Tools and systems
## Rope Physics System
### I implemented a rope physics system from scratch for a 2D game.
- Spring-mass alike rope realistic system.
- Rope collisions (with optimization options).
- Wind force.

<p align="center">
  <img src="https://github.com/AlvaroRoger/PortfolioWebsite.github.io/assets/49962993/0364406d-fb94-47df-90f5-edd4dde41cd2" />
</p>

## Feedbacks Tool
### A system to synchronize game events and vfx.
- Component-based. Different modules based on (GameObject, Unity Events, Particle System, Cinemachine...).
- Different actions for each module (Set Active, Play, Switch Color, Shake...).
- Used in professional projects and in the [Game Feel Task](#game-feel-task).

<p align="center">
  <img src="https://github.com/AlvaroRoger/PortfolioWebsite.github.io/assets/49962993/279120d2-a25f-4eb0-b03f-eea3b4d86ab5" />
</p>

## Global Events Tool
### Implemented an event system to create event objects and instances from the editor.
- With this tool, you can create, edit and remove event objects from editor in a designer-friendly way.
- Events are created with a name, a list of parameters and an icon. Instances of events are created as Scriptable Objects with the selected icon.
- Used in professional projects and in the [Game Feel Task](#game-feel-task).

<p align="center">
  <img src="https://github.com/AlvaroRoger/PortfolioWebsite.github.io/assets/49962993/c8ea8fb0-a796-4f3c-8cae-a2fe24d5e9af" />
  <img src="https://github.com/AlvaroRoger/PortfolioWebsite.github.io/assets/49962993/fe9d14fb-8197-4635-a587-96a832472640" />
</p>

## Save System
### Save system ready to save in all platforms
- Abstracted from gameplay code.
- Optimized: load and save by types, to reduce time and memory use.
- Easy to configure and debug from editor.

<p align="center">
  <img src="https://github.com/AlvaroRoger/PortfolioWebsite.github.io/assets/49962993/04a9cb7b-a751-406b-9feb-03509df896e9" />
</p>

## Procedural Path Generation
### Optimized algorithm to find networks of paths.
- Backtracking algorithm.
- Setup parameters: number of floors, global branch percentage, branch percentage multiplier by depth (with an animation curve)...
- Every path meets the designer's rules.

<p align="center">
  <img src="https://github.com/AlvaroRoger/PortfolioWebsite.github.io/assets/49962993/e67f9621-489d-44d9-b1c5-0cb727036f56" />
</p>

# Some projects where I worked on shaders
## Game Feel Task
### Task I made for a gameplay programmer position.
#### They gave me a simple scene with the standard pipeline and some models and asked me to create some "game feel" out of that.
- Decided to create some gameplay, so it could feel natural.
- Migrated the project to Universal Render Pipeline.
- Created some particles and shaders to give more feedback to the player.

<p align="center">
  <img src="https://github.com/AlvaroRoger/PortfolioWebsite.github.io/assets/49962993/2a2bebc0-7397-4fe6-b7b7-87ad1501b7db" />
</p>

## Miaumba
### PvP local game where two cats fight for staying on the top of a falling toast! (wow so cool)
- Designed and programmed the game.
- Implemented wind and ground pound effects.
- Solved movement huge problems.
  #### [Play the game!](https://alvaro-roger.itch.io/miaumba-sgdjam2)

<p align="center">
  <img src="https://github.com/AlvaroRoger/PortfolioWebsite.github.io/assets/49962993/efdbfe13-7845-44c1-ae6d-dcfa45383a88" />
  <img src="https://github.com/AlvaroRoger/PortfolioWebsite.github.io/assets/49962993/94b91c2c-9a64-4b76-b90f-0134e5ed92ec" />
</p>

# Shader Studies
## Glitch effect - HLSL
### Vertex displacement effect with some bloom.
<p align="center">
  <img src="https://github.com/AlvaroRoger/Alvaro-Roger/assets/49962993/cd9cfcf7-1d3a-4ba9-8330-e73786902b04" />
</p>

## Force Field Shader - Shader Graph
### Force Field shader with hit ripples using Unity's Shader Graph. Followed mainly this [tutorial](https://danielilett.com/2023-02-09-tut6-3-energy-shield/).
<p align="center">
  <img src="https://github.com/AlvaroRoger/Alvaro-Roger/assets/49962993/8424c914-3faa-4910-8322-f39163801eee" />
</p>

## Night in the forest - Shader Graph
### A scene with some shaders like grass, water and outline.
<p align="center">
  <img src="https://github.com/AlvaroRoger/PortfolioWebsite.github.io/assets/49962993/cb33e56b-4583-455a-920e-c6a5122e1794" />
</p>

## Grayscale Effect - HLSL
### A render pass where I applied the dot product between the pixel color and a vec3 representing the grayscale.
<p align="center">
  <img src="https://github.com/AlvaroRoger/Alvaro-Roger/assets/49962993/0d8c415f-d35c-4548-9109-9b3fee5ddebc" />
</p>

## Pixel Effect - Shader Graph
### A render pass where I posterized the URP Sample Buffer.
#### NOTE: I preferred to upload a video instead of a gif so that the effect can be better appreciated.
<video src="https://github.com/AlvaroRoger/Alvaro-Roger/assets/49962993/dbc8358e-d40c-4f73-ab03-623ad028fd72" controls="controls" style="max-width: 730px;">
</video>

## Motion Blur - HLSL
### A render pass where I applied some blur based on the camera position compared to the one from the previous frame.
<video src="https://github.com/AlvaroRoger/Alvaro-Roger/assets/49962993/1956ad8a-4728-49dc-aaf8-613178653fb2" controls="controls" style="max-width: 730px;">
</video>
