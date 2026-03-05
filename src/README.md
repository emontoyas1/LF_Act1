# Automaton Verification

# Javier Andres Sierra - Emmanuel Montoya Salazar

## Environment used
- Operating system: Microsoft Windows `10.0.26200.7840`
- Programming language: Java (OpenJDK `17.0.16`)
- Tools: `javac`, `java`, IDE: IntelliJ IDEA

## How to run the program
1. Open a terminal in the `src` folder.
2. Compile:
   ```bash
   javac Automata.java
   ```
3. Run:
   ```bash
   java Automata
   ```
4. Enter a string using only `a` and `b` when the program asks for it.

## Brief explanation of the algorithm
The program simulates a finite automaton that processes the string character by character.
It starts in an initial state (`0137`) and, depending on each symbol (`a` or `b`), changes state using fixed rules.
If an invalid symbol appears, it moves to the `dead` state.
At the end, it checks whether the final state is among the accepting states (`247`, `8`, `58`, `68`) to decide whether the string is **ACCEPTED** or **REJECTED**.
   