# Eastlake High School — Wolves Data Structures Practice Studios (Unit 2 & Unit 3)

Interactive, self-contained, GitHub Pages-ready "LeetCode-style" Python 3 web applications designed for Eastlake High School's **Data Structures** course.

## Studios Included

### 1. Unit 2 Studio: Data Structures (`index.html` / `ehs_unit2_data_structures_studio.html`)
Covers **Unit 2: Stacks, Queues, Maps (`dict`), Sets (`set`), and Maze Adventure (BFS)**:
- **💻 Coding Problems (12 Problems, 48 Automated `_RR` Unit Tests)**
  1. `[Lesson 1 - Easy]` Implement the Stack Interface (`UserStack` from `list`)
  2. `[Lesson 1 - Easy - RR]` Palindrome Checker (`is_palindrome(text: str) -> bool`)
  3. `[Lesson 1 - Medium - RR]` Parentheses & Bracket Checker (`check_brackets(expr: str) -> bool`)
  4. `[Lesson 1 - Medium - RR]` Reverse Polish Notation Calculator (`eval_rpn(tokens: list[str]) -> float`)
  5. `[Lesson 2 - Easy]` Reverse a Queue Using a Stack (`reverse_queue(q: Queue) -> Queue`)
  6. `[Lesson 2 - Medium]` War Card Game Round Simulator (`play_war(p1_cards, p2_cards, max_rounds) -> str`)
  7. `[Lesson 3 - Easy - RR]` Airport Codes Lookup & Updater (`manage_airports(codes, lookups, new_entries) -> list`)
  8. `[Lesson 3 - Medium - RR]` Group Playing Cards by Rank (`group_cards_by_name(hand: list[Card]) -> dict[str, list[Card]]`)
  9. `[Lesson 3 - Easy]` Letter Frequency Counter (`letter_frequency(words: list[str]) -> dict[str, int]`)
  10. `[Lesson 4 - Medium - RR]` Unique Word Prefixes (`unique_prefixes(words: list[str], length: int) -> set[str]`)
  11. `[Lesson 4 - Medium]` Restaurant Menu & Scorigami Set Operations (`analyze_sets(...) -> dict`)
  12. `[Lesson 5 Project - Hard]` Maze Adventure Shortest Path Solver (`solve_maze(maze, start, end)` with BFS `Queue` of `Stack`s, `deepcopy`, and locked rooms + keys)
- **🧠 Code Tracing & Concept Quiz (8 Questions)**: Warm-up tracing for `Stack` (`"busp"`), combined `Stack` & `Queue`, dictionary reassignments (`eeny`, `meeny`, `mo`, `miney`), nested structures (`movie_collection`), and `set` algebra (`vegetables | fruits`).
- **📚 Study Guide & Cheat Sheet**: Complete reference for ADTs, LIFO vs. FIFO, custom `Stack`/`Queue` interfaces, `dict` (`.get()`, `.setdefault()`, `.items()`), `set` (`.add()`, `.update()`, `.discard()`, `&`, `|`, `-`), and the BFS Queue-of-Stacks Maze template.
- **In-Browser Python 3 Execution (Pyodide v0.25.0)** with pre-loaded `Stack`, `Queue`, `Card`, `MazeRoom`, and `deepcopy`, plus `localStorage` persistence.

---

### 2. Unit 3 Studio: Complexity, Recursion & Backtracking (`ehs_unit3_frq_studio.html`)
Covers **Unit 3: Big-O Complexity, Recursion, and Backtracking (`Decks 1–5`)**:
- **17 Medium-Hard FRQ Problems** (102 `RR - Retake Required` unit tests)
- **Automated EHS Style Grader** (Static AST / Regex Linter enforcing *Rule A: No Loops in Pure Recursion*, *Rule B: No Arm's-Length Recursion*, and *Rule C: State Restoration*)
- **10-Question "Mini-Celebration" Quiz Mode** & **Curriculum Knowledge Base**

## Running Locally

Open `index.html` (Unit 2) or `ehs_unit3_frq_studio.html` (Unit 3) directly in any modern browser, or serve locally:

```bash
python3 -m http.server 8000
```
