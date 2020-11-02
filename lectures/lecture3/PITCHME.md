---

### Lecture 3 - Project Management, SDL 2

- Time Management
- Mapping Game Architecture to SDL 2

---

#### Game App Timeline

What happens from the moment you run a game and until it exits?

---

#### Game Architecture

- Start
- Init
- Input
- Update
- Render
- Destroy
- Exit

---

#### Init

1. Sanity check the system, e.g. graphics hardware
2. Open a Window

When using an engine, even a simple one like xcube2d, everything is handled by it. Now we have to do everything ourselves!

---

#### Open a Window

Question: How can we open a window in a platform agnostic way?

Answer: SDL (Simple DirectMedia Layer)

---

#### SDL

Simple DirectMedia Layer is a library that provides cross-platform access to
hardware, e.g. graphics, input devices, audio devices, networking, etc.

- Written in C
- Competitors are QT, GLFW, SFML and others

---

#### Compiling and linking with SDL

We have to tell the compiler where SDL2 headers are (depending on the installation) and how to link against SDL2.

```
$ g++ -c Main.cpp -I /usr/include/SDL2/
$ g++ -o main Main.o -l SDL2
```

Visual Studio takes care of this for us. Nice!

---

#### Model vs View

- The model is the logic of your game. It doesn't know or care about the view. 
- The view is how the model is drawn. The same model can have multiple views.

Note the similarity to the MVC pattern.

- Generally harder to get the model "right" than the view.
- Drawing is just putting pixels on the screen.

---

#### Multiplayer Architecture

- Server is the Model
- Client is the View

More on networking architecture next week!

---

#### Drawing

Putting a pixel into the memory being mapped to screen.
Typically, 4 bytes RGBA (red, green, blue, alpha).

Game code -> SDL -> OpenGL / Direct3d -> Graphics Driver -> Graphics Hardware

---

#### Render

1. Clear the graphics context
2. For each object in the viewport (partially or fully) draw the pixels of that object.
3. Apply post-processing effects

---

#### How to Manage Time (Case Study)

- Design and build Multiplayer Pong clone

---

#### How to Manage Time (Tasks)

- Decompose one big problem into many smaller ones (OO approach)
- Identify tasks need to complete each problem
- Assign priorities (core or optional) and order

---

#### How to Manage Time (Deadlines)

- Know your deadlines (including other modules)
- Calculate **softer** deadlines from **hard** deadlines

---

#### How to Manage Time (Timeline)

- Estimate how long each core task takes
- Use Gantt chart (or alternative) to map core tasks to timeline
- Consider optional tasks if possible

---

#### How to Manage Time (Quality vs Time)

- Settle for "good enough" and move on
- Swap a complex task for a simple one
- Implement the simplest thing that works, then refine
- Always have a working system
- Avoid burnout

---

#### How to Manage Time (Scoped vs Real-world)

- Fixed tasks vs variable tasks
- Tasks carefully chosen vs unknown territory
- Academic support vs field experts

---

#### Assignment Game Idea

- Can implement 100% now? - Too easy
- Don't know how to implement at all? - Too complex
- Roughly 50-50 know-don't know? - Probably a good idea
---

#### Conclusion

- Managing time - always have a plan
- Identify tasks specific to your game
- Use GitHub repo Milestones and Issues to capture tasks
