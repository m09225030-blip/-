# CS453 - Individual AI Project: After-Hours Cleaning Robot

**Name:** إنتصار محمد معيتيق
**Student ID:** 09225030
**Project:** After-Hours Cleaning Robot
**Variant:** ('B', 'E')
**Closed road:** F
**Room to clean:** S -> A -> C -> F (3 حركات)

## What this project does

A cleaning robot starts at location S on a small campus map (8 locations, one road closed in each student's variant). It must reach its assigned room and clean it. The project models the task (PEAS, state, actions, costs), simulates it, and finds the route with two search algorithms:

- **BFS** (uninformed): finds a route with the fewest moves.
- **A\*** (informed): uses the supplied heuristic table, which is admissible on the assigned map, and finds a route with the same number of moves.

The simulator then executes the route and the `clean` action and checks that the task is complete.

## Files

- `project.ipynb` - the full notebook: Tasks 1, 2, 4, 5, 6, 10 and 11.
- `README.md` - this file.

## Dependencies

Python 3 and its standard library only (`copy`, `collections`, `heapq`, `platform`). No installs, GPU, API keys or physical robot are needed.

## How to run

1. Open `project.ipynb` in Google Colab (File > Open notebook > GitHub, or download it and upload it to Colab).
2. In the first code cell, set `STUDENT_ID = "..."` to your ID as text, keeping leading zeros.
3. Choose **Runtime > Restart session and run all**.
4. Check the output of Task 5 (BFS) and Task 6 (A*): the route, the `clean` action, and `Task complete: True`.

Colab link: [paste the link to project.ipynb in YOUR repository]

## Sources and AI assistance

The map, variant helper and heuristic tables come from the CS453 two-week project workbook. I used an AI assistant (Claude) to help draft the explanations and the code; I checked it by reading and explaining each function and by running the edge-case tests in the notebook. Details are in Section 10 of the notebook.
