## Console Renderer (PBR)

ConsoleRenderer is a custom 3D graphics engine I developed in C# that renders dynamic scenes directly into a standard text console. Rather than relying on traditional hardware-accelerated APIs like OpenGL or DirectX, I engineered the project from the ground up as a software rasterizer. The engine manually calculates 3D geometry and projects it into a grid of colored block characters using ANSI escape codes, effectively transforming the standard command prompt into a functional display screen.

Despite the inherent visual and performance constraints of a terminal interface, I designed the engine to support several advanced graphical features typical of modern rendering pipelines. The architecture includes interactive camera controls, a scene graph for managing multiple objects, and depth buffering for accurate occlusion. Most notably, I implemented a Physically Based Rendering (PBR) lighting model, enabling the simulation of realistic material properties—such as metallic reflections, surface roughness, and emissive light sources—entirely through console text.

<img width="672" height="445" alt="ezgif-51ec3ca5f5df6bdb" src="https://github.com/user-attachments/assets/856ad657-0d2c-4c71-8b8e-18c98deb057c" />

## Minecraft Clone (Without Textures)

Minecraft Clone is my custom built voxel sandbox engine, written from scratch in C# and OpenTK. <br> 
Chunks are generated async in the background and uploaded on the main thread. <br> 
It uses Multi Draw Indirect so that I can batch what to draw and then send to the GPU at once. <br> 
I started this project thinkiing I will use the newest OpenGL features and make something optimized. It runs 200 FPS on my laptop with an integrated GPU, so for now, great success.

<img width="1280" height="720" alt="ezgif-2604977eabe6a15c" src="https://github.com/user-attachments/assets/d9ceecc4-7a57-436d-8e77-cf4c0639de67" />


## 2D RPG Game (Survival)

2D RPG Game I made when I didn't have internet at home. I had to reinvent the Math function Atan2 without any external source. <br>
All textures (except for the player) are homemade. For the player, I opened up a game and copied the pixel art of the character. 

<img width="428" height="432" alt="ezgif-2f9df2c53e9de2f2" src="https://github.com/user-attachments/assets/62a31b5b-d99d-4486-8269-18b3c17724d3" />

