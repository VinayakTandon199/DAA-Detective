# DAA Detective: Crack the Case with Algorithms

An interactive, game-style **Design and Analysis of Algorithms (DAA)** project built with **HTML, CSS, and JavaScript**. Every case is a mystery, every algorithm is a clue, and every solved mission moves the investigation forward 🔍🕵️‍♂️💻

## Mission Briefing

The city is under pressure. Hidden patterns, blocked routes, suspicious records, and encrypted messages all point to one truth: the case can only be solved with the right algorithm.

In `DAA Detective`, players step into the role of a digital investigator. Each case file presents a different algorithmic challenge, and the visual execution reveals how the solution works step by step. The goal is not just to finish the case, but to understand why the algorithm succeeds, how efficient it is, and where it belongs in the DAA toolkit.

## How to Play

1. Open the home dashboard and choose an active case file.
2. Read the case briefing to understand the investigation objective.
3. Run the visualization controls and watch the algorithm progress in real time.
4. Follow the log output and highlighted states to track each decision.
5. Review the Time, Space, and Paradigm summary for the algorithm.
6. Submit the case once the correct result is revealed.
7. Earn points, unlock progress, and rise in detective rank as you clear more cases.

## Detective's Toolbelt

These are the algorithms powering the investigation:

- Dijkstra's Shortest Path - finds the fastest route to intercept the suspect.
- 0/1 Knapsack - selects the most valuable evidence within a limited bag capacity.
- Merge Sort - organizes suspect records into a reliable order.
- Backtracking (N-Queens variant) - tests valid guard placements and retracts invalid choices.
- Breadth-First Search (BFS) - searches clue networks level by level.
- Kruskal's MST - builds the minimum-cost monitoring network.
- Branch and Bound (TSP) - prunes weak patrol routes to find the best tour.
- Huffman Encoding - compresses messages for efficient transmission.
- Rat in a Maze - explores paths through blocked escape routes.
- Quick Sort - rapidly partitions and sorts case records.
- Floyd-Warshall - computes shortest paths between every pair of safe houses.
- Longest Common Subsequence (LCS) - identifies shared behavior patterns across logs.
- Topological Sort - orders investigation tasks according to dependency rules.
- Binary Search - locates a target record in a sorted evidence archive.
- Rabin-Karp String Matching - scans intercepted text for hidden patterns.

## Technical Complexity Table

| # | Algorithm | Time Complexity | Space Complexity |
|---|-----------|-----------------|------------------|
| 1 | Dijkstra's Shortest Path | O((V+E)logV) | O(V) |
| 2 | 0/1 Knapsack (Dynamic Programming) | O(n×W) | O(n×W) |
| 3 | Merge Sort (Divide & Conquer) | O(n log n) | O(n) |
| 4 | Backtracking (N-Queens variant) | O(n!) | O(n) |
| 5 | Breadth-First Search (BFS) | O(V+E) | O(V) |
| 6 | Kruskal's MST | O(E log E) | O(V) |
| 7 | Branch and Bound (TSP) | O(n²×2ⁿ) | O(n×2ⁿ) |
| 8 | Huffman Encoding | O(n log n) | O(n) |
| 9 | Rat in a Maze | O(4ⁿ) | O(n²) |
| 10 | Quick Sort | O(n log n) avg | O(log n) |
| 11 | Floyd-Warshall | O(V³) | O(V²) |
| 12 | Longest Common Subsequence (LCS) | O(m×n) | O(m×n) |
| 13 | Topological Sort | O(V+E) | O(V) |
| 14 | Binary Search | O(log n) | O(1) |
| 15 | Rabin-Karp String Matching | O(n+m) | O(1) |

## Key Features

- Cinematic detective-themed interface with particle effects and animated overlays
- 15 interactive algorithm case files
- Real-time execution logs for each investigation
- Complexity summary shown on every case screen
- Difficulty levels and mission points
- Score, solved-cases, and rank tracking
- Progress persistence with browser `localStorage`
- Adjustable global animation speed
- Fully client-side project with no backend and no framework

## Tech Stack

- HTML5
- CSS3 with custom gradients, motion, and theme styling
- Vanilla JavaScript for DOM manipulation and visualization logic
- Browser Local Storage for score and progress persistence

## Project Structure

```text
DAA Project/
|-- index.html
|-- style.css
|-- script.js
|-- README.md
```

## How to Run Locally

1. Clone or download this repository.
2. Open the project folder.
3. Open `index.html` directly in your browser.

No installation, build step, or dependencies are required.

## Learning Value

This project helps students:

- understand core DAA paradigms such as Greedy, Dynamic Programming, Graph, Backtracking, and Divide & Conquer
- connect theory with visual execution
- compare complexity tradeoffs in practical scenarios
- learn through interactive storytelling instead of static notes

## Suggested GitHub Topics

`algorithms`, `daa`, `javascript`, `html`, `css`, `visualization`, `dynamic-programming`, `graph-algorithms`, `backtracking`, `sorting`, `educational-project`

## Author Note

Built as a creative academic project to make DAA concepts easier, visual, and memorable through a detective-case experience.
