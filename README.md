# Eastlake High School — Data Structures Unit 3 FRQ & Big-O Practice Studio

An interactive, self-contained LeetCode-style web application for practicing Python 3 Free Response Questions (FRQs), static style rules, and Big-O complexity analysis for **EHS Data Structures Unit 3: Complexity, Recursion, and Backtracking** (`Decks 1–5`).

## Features

1. **Split-Pane FRQ Practice Arena (17 Medium-Hard Problems)**
   - **Left Pane**: Problem prompt, function signature, concrete input/output trace examples, **Course Style Warning Box**, **3 Progressive Collapsible Hints** (*Hint 1: Base Case*, *Hint 2: Recursive/Choose Step*, *Hint 3: Unchoose/Complexity*), and a hidden **Reference Solution & 5-Point EHS FRQ Rubric** tab with interactive self-scoring.
   - **Right Pane**: Python 3 code editor with line numbers, **Exam Mode (No Autocomplete)** toggle to simulate handwritten FRQ exams, interactive **Big-O Complexity Verification** dropdown, **Automated EHS Style Grader**, and **6 `RR - Retake Required` Unit Tests** per problem (102 total tests).
2. **In-Browser Python 3 Execution Engine + Pyodide Wasm Support**
   - Runs all 17 FRQ problems and 102 `RR - Retake Required` unit tests directly in the browser with call-stack depth tracking (`RecursionError` on linear recursion for $10^8$) and step-limit protection (`TimeoutError` on naive $O(3^n)$ tree recursion).
3. **Automated EHS Style Grader (Static AST / Regex Linter)**
   - **Rule A (No Loops in Pure Recursion)**: Disallows `for`/`while` loops and comprehensions in pure recursive problems.
   - **Rule B (No Arm's-Length Recursion)**: Enforces Deck 5 Slide 25 (*"Don't check for weight before your recursive call! Check weight in the base case instead."*).
   - **Rule C (State Restoration Check)**: Verifies that in-place backtracking mutations (`.pop()`, `.append()`, `maze[r][c] = '@'`, `board[row][col] = 'Q'`) are paired with their corresponding Unchoose restorations (`.add()`, `.insert()`, `maze[r][c] = cell`, `board[row][col] = '.'`).
4. **"Mini-Celebration" Quiz Mode (10 Questions)**
   - Covers `insert_n_ones` ($O(n^2)$ hidden loop), `looped_search` ($O(m \log n)$), `mystery(11)` call-stack unwinding, `faster_power` redundant-call trap, `move_tower`, in-place `subset_sum_exists`, `additive_sequence` ($O(n)$ vs $O(2^n)$), `get_permutations1` ($O(n \cdot n!)$) vs `get_permutations2` ($O(n!)$), and Slide 25 Arm's-Length Recursion.
5. **Curriculum Knowledge Base Tab (Decks 1–5)**
   - Complete quick-reference cards extracted from all 5 lecture slide decks.

## Running Locally

Open `index.html` directly in any modern browser, or serve locally:

```bash
python3 -m http.server 8000
```
