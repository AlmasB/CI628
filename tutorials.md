#### Tutorial 1

Note: take breaks at regular intervals between tasks.

Note: you may wish to have [cppreference](https://en.cppreference.com/w/) open.

1. Create a sample "hello world" project in Visual Studio 2019 in C++.
1. Create a multiplication table program that outputs 10 columns and 10 rows.
1. Create a program that randomly generates a number and then tells you whether it's even or odd.
1. Create a program that reads your input and appends a string to it.
1. Create a "Guess the number" game using code from above programs.

---

#### Tutorial 2

Note: take breaks at regular intervals between tasks.

1. Create a sample "hello world" project in Visual Studio 2019 in C++.
1. Clone and build the assignment code. 
1. Run / play the assignment game example and skim through the code.
1. Read the assignment brief.
1. Think about your client game that you will develop. 
1. Discuss with your neighbour your vision for the game. 
1. On your own (refine) your ideas.
1. Quick-fire on the spot presentations. (a few sentences per person)
1. Background research (see what you can find online about existing multiplayer games).
1. Make notes about your research and thoughts into a document and leave this until next week.

---

#### Tutorial 3

Note: take breaks at regular intervals between tasks.

1. Read the assignment brief. (yes, again :) )
1. Create a Word (or alternative) document. Add a title page.
1. Add a Table of Contents page.
1. Add another page with a few sentences related to your game vision idea and how it might be implemented.
1. Make sure you can build and run the code that is provided as part of the assignment.
1. Consider the existing code to see where your new code might reside.
1. Start designing (on paper) what the game will look like (visually) and how it will work (architecture, software design, classes).
1. By the end of this tutorial, you should have a strong idea of what you are going to do. It is fine if you don't yet know how to implement it.

Homework: if you don't have a strong idea, make sure you spend as much time on it as needed, so that you are happy with your idea by the start of next week.

---

#### Tutorial 4

Note: take breaks at regular intervals between tasks.

1. (Optional but recommended) Create a fork of CI628-PongClient under your GitHub account. This is where you will be developing your assignment work. Remember to back up, **computer scientists do not lose data!**
1. Last week you started reading a bit of the codebase. Now read through all of the codebase and consider where the major parts, such as the main loop, graphics drawing and input, are located.
1. By the end of this tutorial, you should be able to build, run and extend the given code. Add some code to the assignment code base, such as the one shown in the tutorial demonstration.

Homework: it is important that the above statement is true, so ensure it is by next week.

---

#### Tutorial 5

Note: take breaks at regular intervals between tasks.

1. Using previously designed classes, start formulating their relationship to each other. For example, you might need a class `GameObject` to store entities and another class `Texture` to allow usage of 2d images. How do they talk to each other in order to work together?
1. Consider all possible members of the class `GameObject`, e.g. x, y, width, height, other members as needed. Start adding this new class to `MyGame.h/.cpp`. Ensure that at any stage, you can still compile and run the application. If not, go back, otherwise you might spend ages debugging it!
1. By the end of this tutorial, you should have a new class `GameObject` (or different `Actor`, `Entity`, `Node`, depending on how you are designing it) inside `MyGame` files.


---

#### Tutorial 6 (Catch-up)

Note: take breaks at regular intervals between tasks.

There is no code addition today to allow everyone to catch up.

1. Check you are keeping up with the workload and know what needs to be done and when. If in doubt, ask!
1. Pick a multiplayer game you've played recently. Read about its implementation, specifically with respect to how they handle multiplayer data.
1. Find a YouTube or GDC video on multiplayer programming. Watch it fully and email me a 2-3 sentence summary of what you took away from that video.
1. (advanced, optional) Check SDL_net [example demos](https://www.libsdl.org/projects/SDL_net/docs/demos/) and read through the code. Is there something interesting, is there something you can use to potentially modify the assignment game?

---

#### Tutorial 7

Note: take breaks at regular intervals between tasks.

1. See how the networking communication is done between client and server. What data structures are being used and why?
1. Having studied how player input travels from client to server, can you add full player 1 input, so we can move up _and_ down.
1. Can you repeat the same for player 2, should be easy now?
1. Check out what data is being sent from the server to the client. Consider how you might use this data to implement your game idea.
1. Make some notes about what you've done today in the report, particularly commenting on the data structures and networking operation.

---

#### Tutorials 8+

Note: take breaks at regular intervals between tasks.

You should now have enough working knowledge of the assignment code to start experimenting with your game idea. Start adding images, fonts, sounds and other visual and gameplay aspects.

All tutorials from now will focus on the assignment game to ensure you can submit before the deadline.

---