# DS212 OOP Sprint: Group Coding Competition

A zero-dependency Jupyter Notebook repository built for a **60-minute peer tutoring session** on **Object-Oriented Programming (DS212)** at the University of Science and Technology of Southern Philippines (USTP).

Designed for computer labs without a projector: every student clones this repository onto their own PC and opens `00_quick_reviewer.ipynb` (or the live slide deck at [https://troge-dev.github.io/ds212-oop-competition/](https://troge-dev.github.io/ds212-oop-competition/)) as an interactive screen guide before competing in their assigned group notebook.

---

## 1. Quick Setup (On Each Student PC)

Open a terminal (Command Prompt, PowerShell, or VS Code Terminal) and run:

```bash
git clone https://github.com/Troge-dev/ds212-oop-competition.git
cd ds212-oop-competition
```

Open the folder in **VS Code** or **JupyterLab**. No `pip install` or virtual environment setup is required—every notebook uses pure Python standard library.

---

## 2. Repository Contents & Group Assignments

| File | Assigned To | Theme / Focus |
| :--- | :--- | :--- |
| `00_quick_reviewer.ipynb` | **Everyone** | Live 12-minute review of Encapsulation, Inheritance, and Polymorphism |
| `group_1_battle_arena.ipynb` | **Group 1** | Turn-Based RPG Combat Engine (`Fighter`, `Warrior`, `Mage`, `TrapTurret`) |
| `group_2_flood_dispatch.ipynb` | **Group 2** | CDO Flood & Weather Dispatch (`WeatherStation`, `RainGauge`, `RiverSensor`, `CitizenSMSReport`) |
| `group_3_campus_pos.ipynb` | **Group 3** | Campus Coffee & Print POS (`OrderTicket`, `StudentOrder`, `BulkOrder`, `PromoVoucher`) |
| `group_4_library_system.ipynb` | **Group 4** | Campus Media & Loan Queue (`MediaItem`, `PrintedBook`, `AudioBook`, `LabEquipmentKit`) |
| `group_5_data_pipeline.ipynb` | **Group 5** | Mini Data Preprocessing Pipeline (`DatasetBatch`, `ScaleStep`, `ClampStep`, `DropNegativesStep`) |

---

## 3. Competition Rules & Scoring (100 Points Total)

Every group solves **all three core OOP concepts** inside its unique theme:

1. **Task 1 — Encapsulation `[30 pts]`**: Protected attributes (`_attr`), read-only `@property` getters, defensive `tuple` returns for collections, and `@property.setter` validation raising `ValueError`.
2. **Task 2 — Inheritance `[35 pts]`**: Subclassing with `super().__init__()`, overriding methods cleanly, and extending parent output with `super().method()`.
3. **Task 3 — Polymorphism & Duck Typing `[35 pts]`**: Eliminating `if isinstance(...)` chains in favor of a unified loop that also accepts a standalone duck-typed class.

### Winning Condition
* Run each `# RUN THIS CELL TO VERIFY TASK X` cell (`Shift + Enter`) to verify your solution in real time.
* Run the **Final Scoreboard** cell at the bottom of your notebook.
* A team wins when **all members on its PCs achieve `100 / 100 pts`** (or highest team average completion at the end of 35 minutes). Help teammates sitting near you!

---

## 4. Session Timeline (60 Minutes)

| Time | Phase | Activity |
| :--- | :--- | :--- |
| **00:00 – 00:04** | Setup | Clone the repository and open `00_quick_reviewer.ipynb`. |
| **00:04 – 00:16** | Quick Reviewer | Guided verbal walkthrough of the 3 core concepts on your monitor. |
| **00:16 – 00:50** | Group Competition | Open your assigned `group_X_*.ipynb`, fix all 3 tasks, and verify `100 / 100`. |
| **00:50 – 01:00** | Debrief & Wrap-Up | Cross-group explanation of the hardest bugs and announcement of winners. |

---

## 5. Course Reference

Aligned with **Module 04 (Four Core Concepts of OOP)** in the DS212 course companion:
- [DS212 Course Companion — Jhun Brian](https://jhunbrian.github.io/ims/oop/notebooks/06_CoreConcepts.html)

---

## Author

- **Rogelio Q. Mandamian III** (`Troge-dev`) — BS Data Science, USTP
