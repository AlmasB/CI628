---

### Lecture 6 - (Catch-up) Good Programming Practices

How to write ...

- ~~good~~ _not bad_ code
- robust code
- maintainable code

---

#### Last Weeks Recap

- Assignment
- C++
- Multiplayer

---

#### Software Design

- Capture goals and data
- Flexible - requirements change
- Modular units
- YAGNI, KISS, DRY
- When in doubt, go for simple, most direct solution

---

#### Classes

- Short
- Single Responsibility Principle
- Encapsulate data
- Abstract layers (interfaces vs implementations)

---

#### Functions

> "FUNCTIONS SHOULD DO ONE THING. THEY SHOULD DO IT WELL. THEY SHOULD DO IT ONLY."

- Short

---

#### Comments / Documentation

- Only if it adds value
- Explain intent (why and **NOT** what)
- Keep up to date, or don't keep at all

---

#### Using 3rd Party Code

Write new code only if

- library too complex for use case
- library doesn't cover use case fully

When using a library isolate via own bridge / adapter

---

#### Exceptions

- Input validation
- Don't muddle exceptions and logic

---

#### Workspace and Code

- Clear project directory structure
- Source code management
- Build (dependency management) tools
- Consistent indentation
- Naming conventions

---

#### Testing

- Test the interface, **NOT** the implementation
- Test the code, **NOT** the language
- Should be small (one feature), fast and serve as a specification
- Easier refactoring

---

#### Test Driven Development

- Red, Green, Refactor
- Works best when specification is clear and well-defined
- The test is written before the code
- Successive refinement (incremental, the system always works / passes tests)

---

#### Continuous Integration

- Automates the process
- Early and frequent integrations avoid "merge/integration hell" to an extent
- Examples: Travis, Jenkis, AppVeyor

---

#### Case Study (Simple Game)

- Refactor existing dirty-ish codebase to be cleaner

---

#### Conclusion

- Can't replace experience (expect to put in hours), but ...
- Can avoid writing _some_ bad code by following guides
- Don't alter the problem to fit the pattern, alter the pattern to fit the problem

----

#### Further Reading

- Clean Code
- [Game Programming Patterns](http://gameprogrammingpatterns.com/contents.html)

---

#### Tutorial

- Clean up your code
