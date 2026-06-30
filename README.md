## Console Renderer (PBR)

ConsoleRenderer is a custom 3D graphics engine I developed in C# that renders dynamic scenes directly into a standard text console. Rather than relying on traditional hardware-accelerated APIs like OpenGL or DirectX, I engineered the project from the ground up as a software rasterizer. The engine manually calculates 3D geometry and projects it into a grid of colored block characters using ANSI escape codes, effectively transforming the standard command prompt into a functional display screen.

Despite the inherent visual and performance constraints of a terminal interface, I designed the engine to support several advanced graphical features typical of modern rendering pipelines. The architecture includes interactive camera controls, a scene graph for managing multiple objects, and depth buffering for accurate occlusion. Most notably, I implemented a Physically Based Rendering (PBR) lighting model, enabling the simulation of realistic material properties—such as metallic reflections, surface roughness, and emissive light sources—entirely through console text.

<img width="672" height="445" alt="ezgif-51ec3ca5f5df6bdb" src="https://github.com/user-attachments/assets/856ad657-0d2c-4c71-8b8e-18c98deb057c" />
