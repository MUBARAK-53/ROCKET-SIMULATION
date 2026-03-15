# ROCKET-SIMULATION
🚀 Rocket Physics Simulator (OpenGL + GLFW)  Real-time 2D rocket simulation featuring realistic thrust/gravity physics, complete rocket model (body, nose cone, fins, animated flames), and smooth 60fps rendering using C++, legacy OpenGL immediate mode, and GLFW window management. 
 🚀 Rocket Physics Simulator (OpenGL + GLFW)

Real-time 2D rocket simulation with realistic **thrust/gravity physics** using **legacy OpenGL** and **GLFW**.

## ✨ Features
- Physics engine: thrust (0.17), gravity (-0.16), velocity integration
- Rocket components: body, nose cone, fins, animated flames
- Continuous flight loop (resets at 0.9 height)
- Smooth 60fps rendering (1000x700 viewport)


## 🛠️ Tech Stack
C++11 | GLFW3 | Legacy OpenGL (immediate mode)
g++ compiler | MinGW-w64 linking



## 🚀 Quick Start
```bash
g++ Practice_sim.cpp -o rocket_sim.exe -Iglfw\include -Lglfw\lib-mingw-w64 -lglfw3 -lopengl32 -lgdi32 -luser32
./rocket_sim.exe
🎮 Controls
No input needed - Auto physics simulation

Window: ESC/Close to exit

📚 Learning Outcomes
GLFW window management + OpenGL context

Matrix stack (Push/Pop, Translate, Scale)

Physics integration (velocity += acceleration × dt)

Primitive drawing (QUADS, TRIANGLES, LINES)

