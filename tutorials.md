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

1. Clone (or download zip, link on MyStudies) and build the assignment code. Refer to recording of lecture 1.
1. Run / play the assignment game example and skim through the code.
1. Read the assignment brief.
1. Think about your client game that you will develop. 
1. Discuss with your peer on Teams (written chat is fine) your vision for the game. 
1. On your own, refine your ideas.
1. Background research (see what you can find online about existing multiplayer games).
1. Can you think of a way to improve the current client? Start thinking around adding images, sounds, special effects. How do you know when to play a sound or where to show the image?
1. Make notes about your research and thoughts into a document and leave this until next week.
1. Add full movement to player1.
1. Consider you might add a second player.

---

#### Tutorial 3

Note: take breaks at regular intervals between tasks.

1. Read the assignment brief (particularly the assessment criteria).
1. Create a Word (or alternative) document. Add a title page.
1. Add a Table of Contents page.
1. Add another page with a few sentences related to your game vision idea and how it might be implemented.
1. Make sure you can build and run the code that is provided as part of the assignment.
1. Consider the existing code to see where your new code might reside.
1. Start designing (on paper) what the game will look like (visually) and how it will work (architecture, software design, classes).
1. By the end of this tutorial, you should have a strong idea of what you are going to do. It is fine if you don't yet know how to implement it.
1. If you don't have a strong idea, make sure you spend as much time on it as needed, so that you are happy with your idea by the start of next week.

---

#### Tutorial 4

Note: take breaks at regular intervals between tasks.

1. (Optional but recommended) Create a fork of CI628-PongClient under your GitHub account. This is where you will be developing your assignment work. Remember to back up, **computer scientists do not lose data!**
1. Last week you started reading a bit of the codebase. Now read through all of the codebase and consider where the major parts, such as the main loop, graphics drawing and input, are located.
1. By the end of this tutorial, you should be able to build, run and extend the given code. As the one shown in the lecture demonstration, ensure you can easily navigate all parts of the code. If you missed the lecture, it's available from Teams. It is important that by next week you know exactly where to write new code and how to extend existing code.
1. Start adding empty classes that you might need in the game: e.g. Bat, Ball, or generic GameObject, etc. These go into MyGame.h/.cpp. Note that creating classes such as Player (which wraps SDL types) can help demonstrate you know OO principles in game development, which in turn will attract higher marks, rather than using built-in SDL types, such as SDL_Rect.

---

#### Tutorial 5

Note: take breaks at regular intervals between tasks.

1. Using previously designed classes, start formulating their relationship to each other. For example, you might need a class `GameObject` to store entities and another class `Texture` to allow usage of 2d images. How do they talk to each other in order to work together?
1. Consider all possible members of the class `GameObject`, e.g. x, y, width, height, other members as needed. Start adding this new class to `MyGame.h/.cpp`. Ensure that at any stage, you can still compile and run the application. If not, go back, otherwise you might spend ages debugging it!
1. By the end of this tutorial, you should have a new class `GameObject` (or different `Actor`, `Entity`, `Node`, depending on how you are designing it) inside `MyGame` files.
1. Ensure that you know where to read server messages and have a few thoughts on how you might handle them. For example, the server will tell you when a wall was hit, perhaps note this for the future, so you can play a sound.


---

#### Tutorial 6 (Catch-up)

Note: take breaks at regular intervals between tasks.

There is no code addition today to allow everyone to catch up.

1. Check you are keeping up with the workload and know what needs to be done and when. If in doubt, ask!
1. Pick a multiplayer game you've played recently. Read about its implementation, specifically with respect to how they handle multiplayer data.
1. Find a YouTube or GDC video on multiplayer programming. Watch it fully and write 2-3 sentence summary of what you took away from that video in your report.
1. (advanced, optional) Check SDL_net [example demos](https://www.libsdl.org/projects/SDL_net/docs/demos/) and read through the code. Is there something interesting, is there something you can use to potentially modify the assignment game?

---

#### Tutorial 7

Note: take breaks at regular intervals between tasks.

1. See how the networking communication is done between client and server. What data structures are being used and why?
1. Having studied how player input travels from client to server, you added (do this now if you didn't) full player 1 input, so we can move up _and_ down.
1. Can you repeat the same for player 2, should be easy now? (do this now if you didn't)
1. Check out what data is being sent from the server to the client. Consider how you might use this data to implement your game idea.
1. Make some notes about what you've done today in the report, particularly commenting on the data structures and networking operation.
1. What algorithms / concepts / ideas did you take away from last week's research? Think how you can adapt them to feature in the game. Remember, to achieve an A-band grade, you will need to demonstrate some original ideas / implementation.

---

#### Tutorials 8-12

Note: take breaks at regular intervals between tasks.

You should now have enough working knowledge of the assignment code to start experimenting with your game idea. Start adding images, fonts, sounds and other visual and gameplay aspects. Current and future workshops will help you with _some_ of these aspects. The others are for you to explore independently.

All tutorials from now will focus purely on the assignment game to ensure you can submit before the deadline. Ensure you spend tutorial time wisely and always refer to the assignment brief to see where/how you can gain marks.

---