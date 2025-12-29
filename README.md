# HolaMundoServer: Continuous Flow (Echo Server)

## Project Description

This is an **educational application** based on Client-Server architecture.

In this activity, we **reuse the code from the HolaMundoServer repository** but add a key modification: **continuity**. The goal is for the server to not close the connection after the first greeting, but to **continuously accept messages from the client and return them exactly as received** (an "Echo" server).

This serves to understand the basic persistent data flow and how to keep a TCP connection alive.

---

## Structure

The project maintains the two main actors:

- **`Server.java`**: Modified to enter a listening loop, repeating everything it receives.
- **`Client.java`**: Modified to allow the user to send multiple consecutive lines of text.
