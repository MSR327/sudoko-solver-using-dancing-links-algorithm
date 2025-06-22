# sudoko-solver-using-dancing-links-algorithm
## Sudoku Solver with Dancing Links (DLX)
This is a simple and fast Sudoku solver written in C++. It uses Donald Knuth’s Dancing Links (DLX) algorithm under the hood a really clever way to tackle exact cover problems like Sudoku. If you’re into algorithms or just want to see a different approach to solving puzzles, you might find this interesting.

---

**How does it work?**

- The Sudoku puzzle is turned into a big matrix of possibilities, and the DLX algorithm works its magic to find the solution by covering and uncovering options super efficiently.
- Instead of brute-forcing every possibility, DLX keeps track of options using a special linked list, making backtracking lightning fast.
- The code can handle any standard 9x9 Sudoku you throw at it.

---

**Why Dancing Links?**

- It’s fast. Even the toughest Sudoku puzzles get solved in milliseconds.
- The algorithm is elegant and fun to study if you’re into data structures.
- It’s a cool example of how “hard” problems can become simple with the right approach.

---

**How to use**

1. Clone this repo.
2. Compile `sudoko.cpp` with your favorite C++ compiler.
3. Run it and input your puzzle. The program will spit out the solution (or tell you if there isn’t one).

---

If you’re curious about how DLX works or want to tweak the solver, feel free to dive into the code. Suggestions and improvements are always welcome!

Happy puzzling!
