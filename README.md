### About Me:

Hi. I'm **codeleaded**,
a systems-level developer who enjoys building software that is fast, lightweight, and close to the metal.

Besides **C**, I really like a lot of other programming languages from different types like low-level-languages e.g. **C++**, **Rust**, **Assembly (x64,arm64)**, **Go**, **Zig** or modern languages like **Python**, **Java**, **Kotlin**, **Bash**, **Lua** and **C#**. Projects in these languages are mostly not provided in the profile because its propose is implementations in C-Code.

---

### Why C ?

I primarily work with **C** because I just love C for being really powerful, fast and gives the programmer a lot of control over hardware, especially memory and code-execution. In C everything is explicit, clear and readable. The problem with C is being old and having minimal std-libraries.

Solving this problem is my main-goal implementing projects which are build up by hand using only some libc
functions from headers like **stdio.h**, **stdlib.h**, **string.h**, etc.
A lot of functions provided by these headers have a equivalent implementation in my library-collection f.e intrinsic functions like **memcpy** and **memset** or format- and parsing-functions like **sprintf**, **itoa**.

---

### How is the library-collection structured ?

Building libraries and abstracting behavior and later reusing them is the core of programming. This is the reason why the library-collection is seperate and every projects uses absolute paths which are poiting to the header. The library-collection consists only of C-Header files (headerbased only). The reason is that this keeps the code compact and well structured (seperating the C-Code in .h and .c files if needed would be really easy).

The prefix **Cmd_** indicates a commandline like implementation of the tool, no gui like a window etc.
Implementations with **Gui_** on the other hand always contains a window or other gui-components.

Not every library is defined for every combination of architekture and operating-system. The most projects are build for x64, Ubuntu (GNU-Linux) and some for Windows (10/11).
MacOS and Emscripten is not supported (yet).

---

### Datastructures:

- array
- vector
- (bin)tree
- deque
- set
- list
- queue
- stack
- heap
- graph
- hashmap
- dictionary
- database

---

### Libraries:

- a allocator with block optimisations
- cli argument tool
- audio lib for I/O
- camera lib for I/O
- controler input (PS4)
- encryption a/sym
- gui components
- custom markup-language interacting with gui components (.alxml)
- custom compiled-language (SuperALX .salx)
- custom sql-like-language (.alxql)
- custom interpreted-language (LuaLike .ll) used for a pong implementation, graph plotter like desmos
- custom interpreted-language changed for excel like application
- custom interpreted-language changed for robot-karol like application
- object-notation language
- parser for languages
- indemediate representation and VM for IR
- keyboard/mouse interaction
- neuralnetwork for RL and SL (imageCF, pong-bot)
- dumper for objects
- regex engine
- terminal engine for rendering and input
- compression zip
- image-processing
- affine-transform
- AR/opticalflow
- pathfinder astar,wavepropagation
- balls/edges physics-engine
- boids behavior engine
- chess engine
- debug menu tools
- fluid-simulation
- FSB-dithering
- popup menu
- dataset plotter
- voxel-engine
- office-(math)-markup-language
- quadtree
- raycasting engine
- robotic arm (6 DOF Servos AVR and simulation)
- static achses thereom SAT
- shell emulator
- perlin- and sinenoise
- splines and curves (f.e. bezier)
- virtual operating system
- fixed point lib
- networking for games and webservers
- sprite-, shape- and fontrendering
- window-engine for X11 and WinAPI

---

### Implementations: (most of the named libs have a direct impl)
- mario bros like
- minecraft like 3D
- pong
- wolfenstein-raycaster
- dino-game
- astroids game
- cellular automa (game of life)
- mode7
- mandelbrotset with intrinsics
- gravity simulation
- geogebra/desmos
- maze
- editor with syntax highlighting
- pythagorastree
- spining cube
- spining donut
- AR for moving a rect
- 7-segment-clock
- FT for square-wave
- matrix with droping characters
- soundboard

---

Feel free to explore my projects or reach out if you need code which is not provided. Not every mentioned tool is avalible and not every operating system is supported.

---
## 📊 GitHub Stats

![GitHub Followers](https://img.shields.io/github/followers/codeleaded?label=Followers&style=for-the-badge&color=blueviolet)
![Visitors](https://komarev.com/ghpvc/?username=codeleaded&color=blueviolet&style=for-the-badge&label=VISITORS)
![Trophy](https://github-profile-trophy.vercel.app/?username=codeleaded)
