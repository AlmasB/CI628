---

### Lecture 1 - Introduction

- Module Overview
- Content
- C++ recap
- Assessment

---

#### About

- Background: SE and Game Dev
- PhD in CS
- Shipped code in Java, Kotlin, C++, JS & others
- Maintain FXGL game engine
- YouTube game dev channel

---

#### Structure

- Roughly 50%-50% lecture + tutorial per week
- Roughly (50%-50%) C++ / network programming
- Above incorporates feedback from last year

---

#### C++ Importance

- You **will** need a good grasp of C++ to get a decent mark
- Previous feedback suggests we should do **a lot** of C++
- 50% of content is a sensible compromise

---

#### Level 6 (Final Year)

> "Systematic understanding of key aspects"

> "Accurately deploy established techniques of analysis"

> "Ability to manage their own learning"

---

#### Game Architecture

- Main Loop (Input, Update, Render)
- Asset Handling
- Game engine development

---

#### Software Development

- Write clean and robust code
- Good programming practices
- Software design & modular code

---

#### Content Focus

- Pragmatic (only important bits)
- Technology-agnostic
- Language-agnostic

---

#### Tech

- C++
- SDL 2
- Visual Studio 2019
- GitHub + git + cmake (just to set up)

---

#### Networking

- Data Structures
- Serialization
- Error Handling
- Server-Client Architecture Types
- Transport Layer Protocols



---

#### C++ Recap

- Compile & link & run a C++ application
- Variables, Conditionals, Iteration, Printing (terminal)

---

#### Compile

Compiling takes C++ source files and produces an 'object' file.
(Nothing to do with the term 'object' in object-oriented software).

```
$ g++ -c Main.cpp
```

---

#### Link

Linking combines 'object' files into an executable.

```
$ g++ -o Main Main.o
```

---

#### Run

- Double-click on `Main` (`Main.exe` on Windows) in the graphical file manager, or
- `cd` to the containing directory and execute `./Main

---

#### Pragmatic Approach to C++

We will pretend some things do no exist or some things are simpler than they really are.
This approach will help us progress quicker.

---

#### Questions

You should know this from previous modules. Let's recap.

What is ...

- a variable?
- a data type?
- a conditional statement?
- an iteration?

---

#### Recall Java Primitive Data Types

So far, you heavily focused on Java. Let's recap and see how C++ differs.

- Hint 1: there are 8 of them. |
- Hint 2: String is NOT one of them! |
- Hint 3: they start with a lowercase letter. |

---

#### Common C++ vs Java Data Types

- `int` for whole numbers
- `double` for real numbers (e.g. with a decimal point)
- `bool` for Java `boolean` (careful! some old code may use `int` as `bool`)
- `char` for characters (careful with non-English characters)
- `std::string` for literal text (like Java `String`)

---

#### Variables

Declaration and assignment:

```
int x;
x = 7;
```

or

```
int x = 7;
```

---

#### Conditionals

```
if (x <= 0) {
    // x less than or equal to 0
}
```

---

#### Iteration

```
for (int i = 0; i < 10; i++) {
    // runs 10 times
}
```

---

#### Printing to Terminal

Note the `endl;` at the end.

```
std::cout << "Hello World" << std::endl;
```

---

#### Sample Code

```
for (int i = 0; i < 10; i++) {
    if (i < 5) {
        std::cout << "i is less than 5. i is " << i << std::endl;
    }
}
```

---

#### Solve the Problem in C++

Print the following:

```
1 * 10 = 10
3 * 10 = 30
5 * 10 = 50
7 * 10 = 70
9 * 10 = 90
```

---

#### Functions

A program can be divided into small chunks.
These chunks of code are called **functions** (in Java they are called methods):

```
int add(int x, int y) {
    return x + y;
}
```

Note:
- how to pass variables in and out of a function, and
- the scope of variables in a function.

---

#### Functions (example)

Isolate some code and forget about it.

```
void println(std::string text) {
    std::cout << text << std::endl;
}

```

1. Can we add functions to our previous solution?
2. Will it help to make the code more readable?
3. Why yes / no? Any difference if it was a larger piece of code?


---

#### Assessment

- Implement multiplayer Pong client (100%)
- Demo

---

#### Conclusion

- Code in C++
- A lot of games and programming
- Cross-disciplinary
- Challenging but fun
