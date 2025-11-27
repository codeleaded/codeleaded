### About Me:

Hi, I'm codeleaded,
a systems-level developer who enjoys building software that is fast, lightweight, and close to the metal.

Besides **C**, I really like many other programming languages from different categories — such as low-level languages like **C++**, **Rust**, **Assembly (x64, arm64)**, **Go**, **Zig**, and modern languages like **Python**, **Java**, **Kotlin**, **Bash**, **Lua**, and **C#**.
Projects in these languages are mostly not provided in this profile because its purpose is to showcase implementations in **C**.

---

### Why C ?

I primarily work with **C** because I love how powerful and fast it is, while giving the programmer a high level of control over the hardware — especially memory and code execution.
In **C**, everything is explicit, clear, and readable.
The downside of **C** is its age and the minimal standard libraries.

Solving this problem is my main goal by implementing projects that are built by hand using only a few libc functions from headers like **stdio.h**, **stdlib.h**, **string.h**, etc.
Many functions provided by these headers have equivalent implementations in my library collection, e.g., intrinsic functions like **memcpy** and **memset**, or formatting/parsing functions like **sprintf**, **itoa**, etc.

---

### How is the library collection structured ?

Building libraries, abstracting behavior, and later reusing them is the core of programming.
This is why the library collection is separate, and every project uses absolute paths that point to the headers.
The library collection consists only of C header files (header-only). The reason is that this keeps the code compact and well structured (separating the C code into **.h** and **.c** files would be easy if needed).

The prefix **Cmd_** indicates a command-line–like implementation of the tool — no GUI, no window, etc.
Implementations with **Gui_**, on the other hand, always contain a window or other GUI components.

Not every library is defined for every combination of architecture and operating system.
Most projects are built for **x64**, **Ubuntu (GNU/Linux)**, and some for **Windows (10/11)**.
**macOS** and **Emscripten** are not supported (yet).

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

- allocator with block optimisations
- CLI argument tool
- audio lib for I/O
- camera lib for I/O
- controller input (PS4)
- symmetric/asymmetric encryption
- GUI components
- custom markup language interacting with GUI components (.alxml)
- custom compiled language (SuperALX .salx)
- custom SQL-like language (.alxql)
- custom interpreted language (LuaLike .ll) used for a Pong implementation, graph plotter like Desmos
- custom interpreted language modified for an Excel-like application
- custom interpreted language modified for a Robot-Karol–like application
- object-notation language
- parser for languages
- intermediate representation and VM for IR
- keyboard/mouse interaction
- neural network for RL and SL (imageCF, pong-bot)
- dumper for objects
- regex engine
- terminal engine for rendering and input
- compression (zip)
- image processing
- affine transforms
- AR/optical flow
- pathfinder (A*, wave propagation)
- balls/edges physics engine
- boids behaviour engine
- chess engine
- debug menu tools
- fluid simulation
- FSB dithering
- popup menu
- dataset plotter
- voxel engine
- office-(math)-markup language
- quadtree
- raycasting engine
- robotic arm (6 DOF Servos AVR and simulation)
- static axes theorem (SAT)
- shell emulator
- Perlin and sine noise
- splines and curves (e.g. Bézier)
- virtual operating system
- fixed-point library
- networking for games and web servers
- sprite-, shape-, and font rendering
- window engine for X11 and WinAPI

---

### Implementations: (most of the named libs have a direct impl)
- Mario Bros–like
- Minecraft-like 3D
- Pong
- Wolfenstein raycaster
- Dino game
- Asteroids game
- cellular automata (Game of Life)
- Mode 7
- Mandelbrot set with intrinsics
- gravity simulation
- Geogebra/Desmos
- maze
- editor with syntax highlighting
- Pythagoras tree
- spinning cube
- spinning donut
- AR for moving a rectangle
- 7-segment clock
- FT for square wave
- matrix with falling characters
- soundboard

---

Feel free to explore my projects or reach out if you need code that is not provided.
Not every mentioned tool is available, and not every operating system is supported.

---
## 📊 GitHub Stats

![GitHub Followers](https://img.shields.io/github/followers/codeleaded?label=Followers&style=for-the-badge&color=blueviolet)
![Visitors](https://komarev.com/ghpvc/?username=codeleaded&color=blueviolet&style=for-the-badge&label=VISITORS)
![Trophy](https://github-profile-trophy.vercel.app/?username=codeleaded)
