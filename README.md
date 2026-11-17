# Eastlake High School — Wolves Data Structures Practice Studios (Units 1, 2 & 3)

Interactive, self-contained, GitHub Pages-ready "LeetCode-style" Python 3 web applications designed for Eastlake High School's **Data Structures** course. All 3 studios run 100% in the browser using **Pyodide (`v0.25.0`)** with zero backend dependencies and `localStorage` progress persistence.

---

## Live Studios & Links

1. **Unit 1 Studio (`index.html` / `ehs_unit1_celebration_studio.html`) — Celebration of Skills Prep**
   - **Live URL**: https://coastwalker.github.io/EHS-Data-Structure-Practice/ehs_unit1_celebration_studio.html
   - **16 Coding Problems across 4 Categories**:
     - *Category A (Java to Python Syntax, Conditionals & Loops — U1L2)*: `hello_python_world`, `hello_python_world_plus`, `get_values` (reverse step `range`), `count_words` (case-insensitive fruit counter), `find_value` (fix 6 Java-isms), `make_greeting` (default parameters & f-strings).
     - *Category B (Strings, Lists & Comprehensions — U1L3)*: `slice_and_find`, `filter_words_with_char` (list comprehension AST check), `clean_list` (`.pop()` vs `.remove()`), `pick_random_index` (`random.randrange`).
     - *Category C (Classes, Inheritance & Type Hints — U1L3 & U1L4)*: `Dessert` & `SugarCookie` inheritance (`super().__init__`, `//`), Fix the `BeefDish` class, `Calculator` & `CalculatorAwesome` (`remove_twos_from_history`).
     - *Category D (Debugging, `unittest` & Wordle Project — U1L4 & U1L5)*: Debug `L4_buggy_functions.py` (`find_min`, `index_of`, `product_evens`), Write `unittest.TestCase` methods (`TestIndexOf`), and Wordle ANSI Color Formatter (`get_guess_string` with `TextColor`).
   - **Live Java-ism & Convention Linter Banner**: Warns when `;`, `else if`, `true`/`false`, `.equals()`, `this.`, or `camelCase` function names are used.
   - **Searchable Java-to-Python Cheat Sheet** & **12-Question Concept Quiz** (Regression testing, Equivalence Classes, Boundary Cases, `TAG` Code Review model, `self`, `_var` vs `__var`, VS Code Debugger controls).

2. **Unit 2 Studio (`ehs_unit2_data_structures_studio.html`) — ADTs, Stacks, Queues, Maps, Sets & Maze BFS**
   - **Live URL**: https://coastwalker.github.io/EHS-Data-Structure-Practice/ehs_unit2_data_structures_studio.html
   - **12 Coding Problems & 48 Automated `_RR` Tests**: Custom `Stack` & `Queue` implementations, Palindrome Checker, Bracket Checker, RPN Calculator, Reverse Queue, War Card Simulator, Airport Codes (`.get()` / `.setdefault()`), Card Grouping, Letter Frequency, Unique Prefixes, Scorigami Set Operations, and Maze Adventure BFS (`Queue` of `Stack`s with `deepcopy` and locked doors/keys).
   - **8 Warm-Up Code Tracing Questions** & **Unit 2 Cheat Sheet**.

3. **Unit 3 Studio (`ehs_unit3_frq_studio.html`) — Complexity (Big-O), Recursion & Backtracking**
   - **Live URL**: https://coastwalker.github.io/EHS-Data-Structure-Practice/ehs_unit3_frq_studio.html
   - **17 Medium-Hard FRQ Problems (102 `RR` Tests)**, **Automated EHS AST Style Grader** (*Rule A: No Loops in Pure Recursion*, *Rule B: No Arm's-Length Recursion*, *Rule C: State Restoration*), **10-Question Mini-Celebration Quiz**, and **Decks 1–5 Knowledge Base**.

---

## 3-Step Instructions for Deploying to GitHub Pages

1. **Push Files to Your GitHub Repository:**
   Commit and push `index.html`, `ehs_unit1_celebration_studio.html`, `ehs_unit2_data_structures_studio.html`, `ehs_unit3_frq_studio.html`, and `README.md` to the `main` branch of your GitHub repository:
   ```bash
   git add .
   git commit -m "Deploy Eastlake Wolves Data Structures Unit 1, 2 & 3 Studios"
   git push origin main
   ```
2. **Enable GitHub Pages in Repository Settings:**
   On GitHub, open your repository and go to **Settings** $\rightarrow$ **Pages** (in the left sidebar). Under **Build and deployment**, set **Source** to **Deploy from a branch**, select branch **`main`** and folder **`/ (root)`**, and click **Save**.
3. **Open Your Published Web App:**
   After ~60 seconds, your site will be live at `https://<your-username>.github.io/<repository-name>/` (with top navigation buttons linking all 3 units).
