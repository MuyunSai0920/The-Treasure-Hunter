The assignment focuses on planning and the **PDDL (Planning Domain Definition Language)** modeling system.

## 🎯 Project Overview
We implemented the **Treasure Hunter** domain in PDDL, along with several problem instances.  
The goal of this assignment is to model a dungeon where a hero searches for treasure, while dealing with:
- Rooms and connecting corridors (some locked or risky)  
- Keys with different usage limits (1-use, 2-use, or unlimited)  
- Lock-and-key mechanics for colored corridors  
- Treasure located in the goal room

The hero can perform the following actions:
- Move through corridors (if not locked or collapsed)  
- Unlock corridors using the correct key  
- Pick up and drop keys  
- Navigate toward the treasure

## 📂 Repository Structure
plaintext
├── domain.pddl        # Domain definition (actions, predicates, etc.)
├── problem1.pddl      # Provided problem instance 1
├── problem2.pddl      # Provided problem instance 2
├── problem3.pddl      # Provided problem instance 3
├── problem4.pddl      # Custom "difficult" problem (6–9 rooms, >20 moves, all lock colors)
├── report.pdf         # Group report: member info and contributions
└── README.md          # This file
