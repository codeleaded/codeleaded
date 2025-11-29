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

<span style="display:inline-block; width:500px;">**array**</span>
<span style="display:inline-block; width:500px;">**stack**</span>
<span style="display:inline-block; width:500px;">**vector**</span>
<span style="display:inline-block; width:500px;">**heap**</span>
<span style="display:inline-block; width:500px;">**(bin)tree**</span>
<span style="display:inline-block; width:500px;">**graph**</span>
<span style="display:inline-block; width:500px;">**hashmap**</span>
<span style="display:inline-block; width:500px;">**deque**</span>
<span style="display:inline-block; width:500px;">**set**</span>
<span style="display:inline-block; width:500px;">**dictionary**</span>
<span style="display:inline-block; width:500px;">**list**</span>
<span style="display:inline-block; width:500px;">**database**</span>
<span style="display:inline-block; width:500px;">**queue**</span>

---

### Libraries:

<span style="display:inline-block; width:500px;">• allocator with block optimisations</span>
<span style="display:inline-block; width:500px;">• CLI argument tool</span>
<span style="display:inline-block; width:500px;">• audio lib for I/O</span>
<span style="display:inline-block; width:500px;">• camera lib for I/O</span>
<span style="display:inline-block; width:500px;">• controller input (PS4)</span>
<span style="display:inline-block; width:500px;">• symmetric/asymmetric encryption</span>
<span style="display:inline-block; width:500px;">• GUI components</span>
<span style="display:inline-block; width:500px;">• custom markup language interacting with GUI components (.alxml)</span>
<span style="display:inline-block; width:500px;">• custom compiled language (SuperALX .salx)</span>
<span style="display:inline-block; width:500px;">• custom SQL-like language (.alxql)</span>
<span style="display:inline-block; width:500px;">• custom interpreted language (LuaLike .ll)</span>
<span style="display:inline-block; width:500px;">• LuaLike for for a Pong implementation, graph plotter like Desmos</span>
<span style="display:inline-block; width:500px;">• LuaLike for graph plotter like Desmos</span>
<span style="display:inline-block; width:500px;">• LuaLike modified for an Excel-like application</span>
<span style="display:inline-block; width:500px;">• LuaLike modified for a Robot-Karol–like application</span>
<span style="display:inline-block; width:500px;">• object-notation language</span>
<span style="display:inline-block; width:500px;">• parser for languages</span>
<span style="display:inline-block; width:500px;">• intermediate representation and VM for IR</span>
<span style="display:inline-block; width:500px;">• keyboard/mouse interaction</span>
<span style="display:inline-block; width:500px;">• neural network for RL and SL (imageCF, pong-bot)</span>
<span style="display:inline-block; width:500px;">• dumper for objects</span>
<span style="display:inline-block; width:500px;">• regex engine</span>
<span style="display:inline-block; width:500px;">• terminal engine for rendering and input</span>
<span style="display:inline-block; width:500px;">• compression (zip)</span>
<span style="display:inline-block; width:500px;">• image processing</span>
<span style="display:inline-block; width:500px;">• affine transforms</span>
<span style="display:inline-block; width:500px;">• AR/optical flow</span>
<span style="display:inline-block; width:500px;">• pathfinder (A*, wave propagation)</span>
<span style="display:inline-block; width:500px;">• balls/edges physics engine</span>
<span style="display:inline-block; width:500px;">• boids behaviour engine</span>
<span style="display:inline-block; width:500px;">• chess engine</span>
<span style="display:inline-block; width:500px;">• debug menu tools</span>
<span style="display:inline-block; width:500px;">• fluid simulation</span>
<span style="display:inline-block; width:500px;">• FSB dithering</span>
<span style="display:inline-block; width:500px;">• popup menu</span>
<span style="display:inline-block; width:500px;">• dataset plotter</span>
<span style="display:inline-block; width:500px;">• voxel engine</span>
<span style="display:inline-block; width:500px;">• office-(math)-markup language</span>
<span style="display:inline-block; width:500px;">• quadtree</span>
<span style="display:inline-block; width:500px;">• raycasting engine</span>
<span style="display:inline-block; width:500px;">• robotic arm (6 DOF Servos AVR and simulation)</span>
<span style="display:inline-block; width:500px;">• static axes theorem (SAT)</span>
<span style="display:inline-block; width:500px;">• shell emulator</span>
<span style="display:inline-block; width:500px;">• Perlin and sine noise</span>
<span style="display:inline-block; width:500px;">• splines and curves (e.g. Bézier)</span>
<span style="display:inline-block; width:500px;">• virtual operating system</span>
<span style="display:inline-block; width:500px;">• fixed-point library</span>
<span style="display:inline-block; width:500px;">• networking for games and web servers</span>
<span style="display:inline-block; width:500px;">• sprite-, shape-, and font rendering</span>
<span style="display:inline-block; width:500px;">• window engine for X11 and WinAPI</span>

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

```
  ______                   __            __                            __                  __ 
 /      \                 /  |          /  |                          /  |                /  |
/$$$$$$  |  ______    ____$$ |  ______  $$ |  ______    ______    ____$$ |  ______    ____$$ |
$$ |  $$/  /      \  /    $$ | /      \ $$ | /      \  /      \  /    $$ | /      \  /    $$ |
$$ |      /$$$$$$  |/$$$$$$$ |/$$$$$$  |$$ |/$$$$$$  | $$$$$$  |/$$$$$$$ |/$$$$$$  |/$$$$$$$ |
$$ |   __ $$ |  $$ |$$ |  $$ |$$    $$ |$$ |$$    $$ | /    $$ |$$ |  $$ |$$    $$ |$$ |  $$ |
$$ \__/  |$$ \__$$ |$$ \__$$ |$$$$$$$$/ $$ |$$$$$$$$/ /$$$$$$$ |$$ \__$$ |$$$$$$$$/ $$ \__$$ |
$$    $$/ $$    $$/ $$    $$ |$$       |$$ |$$       |$$    $$ |$$    $$ |$$       |$$    $$ |
 $$$$$$/   $$$$$$/   $$$$$$$/  $$$$$$$/ $$/  $$$$$$$/  $$$$$$$/  $$$$$$$/  $$$$$$$/  $$$$$$$/ 
```

---
## 📊 GitHub Stats

![GitHub Followers](https://img.shields.io/github/followers/codeleaded?label=Followers&style=for-the-badge&color=blueviolet)
![Visitors](https://komarev.com/ghpvc/?username=codeleaded&color=blueviolet&style=for-the-badge&label=VISITORS)
![Trophy](https://github-profile-trophy.vercel.app/?username=codeleaded)
