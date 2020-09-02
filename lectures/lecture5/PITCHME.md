---

### Lecture 5 - Multiplayer Game Architecture

- Architecture Types
- Advantages & Disadvantages

---

#### Game Architecture

Question: What does a single player game architecture look like?

---

#### Game Architecture

1. Enter
2. Init
3. Main Loop
4. Destroy
5. Exit

---

#### Main Loop

1. Input
2. Update
3. Render

How does this translate to multiplayer?

---

#### Main Loop (Multiplayer)

1. Client Input
2. Server Update
3. Client Render

What's the catch?

---

#### Network Details

- Internal / External IP
- Port
- Transport Layer Protocol: TCP / UDP
- Packet and data

---

#### Architecture Types 1

Server-Client: (1-1)

- Server is a host and also its own client.
- Limited to two people.
- Easy to implement.

---

#### Architecture Types 2

Server-Client: (1-n)

- Server is typically a headless dedicated server.
- Very common and reasonably easy to implement.

---

#### Architecture Types 3

Server-Client: (m-n)

- Server comprises multiple machines, maybe in different locations.
- Difficult to get the implementation right.

---

#### Question Time

We'll go through assignment code and I will ask you (each student alphabetically) questions about important LoC.

---

#### Implementation Details 1

"Dumb" client

Client is the View / Controller and Server is the Model.

---

#### Implementation Details 2

Client-side prediction

Client interpolates movements based on input.

---

#### Implementation Details 3

Client replication

Objects and data are replicated on the client based
on replication specification.
For example, properties are only replicated when needed.

---

#### Conclusion

In a similar way to single player games, various architecture types exist.
To gain high performance it is crucial to pick the right architecture type.
