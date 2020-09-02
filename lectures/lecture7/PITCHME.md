---

### Lecture 7 - Data Structures

Building Custom Data Structures

---

### Question

What is a data structure?

Name commonly used data structures and their use cases.

---

### How to Design a Custom Data Structure

1. Capture the data needed at both ends (server / client)
2. Normalize - remove extra information that can be computed from existing data
3. Group data by usage, e.g. player data, inventory data, world data, etc.

The resulting types are your data structures.

---

### Example Game - Pong

Design a custom data structure for a multiplayer Pong.

---

### Serialization

Question: what is it and what does it enable us to do?

---

### Serialization Mechanisms

1. Binary Reflection
2. Code generated - Google ProtoBuf
3. Structured Textual - .json, .xml
4. Custom binary / text

---

### Binary Reflection

- Provided for free by the language (typically)
- Data changes may be difficult to handle
- Slow
- Large size
- Unreadable

---

### Code generated

- The code is generated from a specification file
- Data changes mostly easy to handle
- Fast
- Small size
- The specification file is easy to read

---

### Structured Textual

- Apps with GUI exist to generate these files
- Data changes mostly easy to handle
- Fast
- Small size (after compression)
- Easy to read

---

### Custom binary / text

This differs for each implementation, but typically:

- Need to write own implementation
- Data changes mostly difficult to handle
- Very Fast
- Small size
- Unreadable

---

### Compression

The data being sent may have common patterns
or absent values. Such data (especially in text format)
can be **compressed** by an algorithm to reduce size.
For example, AAAAAAAAA can be writeen as A9.

The trade-off is between speed and size.

---

### Encryption

The data being sent can also be **encrypted**.
Encryption can be as primitive as adding a random number to each byte
or as complex as a sequence of operations on bytes based on a key.

The trade-off is between speed and security.

---

#### Conclusion

- Data structures are not difficult
- Libraries exist to handle serialization
- For simple stuff, basic strings / objects are your friends
