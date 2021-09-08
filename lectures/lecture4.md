---

### Lecture 4 - Multiplayer Games

- Introduction to multiplayer
- Detailed overview of assignment code (C++ / Java)

---

#### Structure

- Multiplayer Game Architecture
- Application Layer Architecture
- Data Structures
- Error Handling / Latency

---

#### Architecture Types

Server-Client: (1-1), (1-n), (m-n)

Implementation details: "dumb" client, client-side prediction, client replication

---

#### Data Structures

- Basic Concepts
- Serialization / Deserialization
- Efficiency
- Performance
- Security

---

#### Multiplayer Types

- Co-op
- PvP (Solo, Teams)
- MMO

---

#### General Problems

Question: what problems do we deal with when writing a network based game?

---

#### General Problems

- Code complexity
- Lag
- Out of sync game objects, i.e. invalid state
- Hardware problems (we don't have 100% control over the connection)

---

#### Possible Solutions

- Libraries exist to deal with complex code
- Client can predict behaviour + immediate game response, e.g. animation
- Authorative server
- Robust code to handle exceptions


---

#### Assignment Code Demo

We will now in detail (each LoC!) explore the code. Your task is to:

- read the brief
- ask questions

---

#### Conclusion

- Do not underestimate the complexity of multiplayer
- Make sure you are comfortable with the given code

