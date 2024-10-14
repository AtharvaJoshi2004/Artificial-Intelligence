# CAUA31201: Artificial Intelligence

## Overview
This repository contains assignments for the course **CAUA31201: Artificial Intelligence**. The course covers various key aspects of AI, including search strategies, knowledge representation, reasoning under uncertainty, expert systems, and machine learning. The objective is to provide students with a deep understanding of AI concepts and their practical applications in real-world scenarios.

## Course Information
- **Credits**: 4
- **Lecture (L)**: 3 hrs/week
- **Practical (P)**: 2 hrs/week

### Prerequisites
- Linear Algebra
- Probability and Statistics
- Discrete Mathematics

## Key Course Objectives
- Understand the characteristics and architecture of intelligent agents.
- Explore various AI search strategies.
- Learn techniques for reasoning under incomplete or uncertain information.
- Gain knowledge about expert systems and machine learning techniques.
- Explore AI applications in diverse industries.
- Stay updated on advancements in AI and cloud-based AI solutions.

## Assignments Included
1. Implement DFS and BFS for the 8-puzzle problem.
2. Solve a Constraint Satisfaction Problem.
3. Parse a family tree using a knowledge base.
4. Implement the A* Algorithm for an application.
5. Apply the Minimax Algorithm for game playing.
6. Implement basic search strategies for the 8-Queens Problem.
7. Forward Chaining Algorithm.
8. Backward Chaining Algorithm.
9. Create a chatbot application for a real-world scenario.

## References
### Textbooks:
- Stuart Russell, Peter Norvig, *Artificial Intelligence: A Modern Approach* (4th edition, 2020)
- Elaine Rich, Kevin Knight, Nair, *Artificial Intelligence* (TMH)
- Patrick Henry Winston, *Artificial Intelligence* (Addison-Wesley Publishing)

For additional details, please refer to the course materials provided during the lectures.

# Assignments Overview

This repository contains a series of assignments focusing on different algorithms and problem-solving techniques in computer science and artificial intelligence. Each assignment demonstrates specific methods and applications across various domains.

## Assignment 1: Solving the 8-Puzzle Problem

This assignment demonstrates how to solve the 8-puzzle problem using two fundamental search algorithms: Depth First Search (DFS) and Breadth First Search (BFS).

### Problem Overview
The 8-puzzle is a classic sliding puzzle where the objective is to rearrange numbered tiles in order, with one empty space available to move the tiles around.

### Algorithms Used
- **Depth First Search (DFS)**: Explores as deep as possible before backtracking.
- **Breadth First Search (BFS)**: Explores all possible moves at the current depth before proceeding deeper.

### Steps to Run the Code
1. Clone or download the project files.
2. For solving the puzzle using DFS, execute `8_puzzle_dfs.py`.
3. To see the BFS approach in action, run `8_puzzle_bfs.py`.

---

## Assignment 2: Solving a Constraint Satisfaction Problem (CSP)

This assignment explores how to solve Constraint Satisfaction Problems (CSP) by implementing key algorithms.

### Problem Overview
CSPs are problems where solutions must satisfy a set of constraints. These techniques are widely used in tasks like scheduling, map coloring, and solving logic puzzles.

### Algorithms Used
- **Backtracking Search**: A method to explore possible solutions by trying and eliminating options.
- **Constraint Propagation**: A technique to reduce the search space by enforcing constraints early.

### Steps to Run
1. Download or clone the project files.
2. Execute `csp_solver.py` to solve the given CSP and view the results.

---

## Assignment 3: Building and Querying a Family Tree with a Knowledge Base

This assignment focuses on constructing a family tree and leveraging a knowledge base to parse and query relationships.

### Problem Overview
The task is to represent family relationships in a knowledge base and then use that representation to answer queries about the family structure.

### Tools Implemented
- **Logical Inference Engine**: Performs reasoning based on family relationships.
- **Knowledge Base Parsing**: Parses the family tree data to extract meaningful relationships and allow querying.

### Steps to Run
1. Clone the project repository.
2. Execute `family_tree_parser.py` to construct and query the family tree.

---

## Assignment 4: Pathfinding with A* Algorithm

This assignment demonstrates how the A* algorithm can be applied to solve pathfinding problems in a weighted graph.

### Problem Overview
The A* algorithm efficiently finds the shortest path between two points by combining cost with a heuristic. This assignment showcases how the algorithm solves pathfinding challenges in various scenarios.

### Algorithm Details
- **A* Search**: Incorporates both actual cost and a heuristic to explore the most promising paths first.

### Steps to Run
1. Clone or download the repository.
2. Execute `a_star.py` to run the A* algorithm and observe the pathfinding process.

---

## Assignment 5: Solving the 8-Queens Problem

This assignment explores the application of basic search algorithms to solve the 8-Queens problem.

### Problem Overview
The challenge of the 8-Queens problem is to place 8 queens on a chessboard in such a way that no two queens threaten each other, meaning no two queens share the same row, column, or diagonal.

### Algorithms Implemented
- **Backtracking Algorithm**: Systematically places queens and backtracks when conflicts arise.
- **Basic Search Strategies**: Utilized to explore possible board configurations.

### Steps to Run
1. Clone or download the repository.
2. Run `8_queens.py` to execute the solution and view the placement of the queens.

---

## Assignment 6: Implementing the Forward Chaining Algorithm

This assignment focuses on applying the Forward Chaining algorithm for reasoning and decision-making in a rule-based system.

### Problem Overview
Forward Chaining is an inference method that starts with known facts and applies rules to derive new facts, making it useful for logical reasoning and decision-making tasks.

### Steps to Run
1. Clone or download the repository.
2. Execute `forward_chaining.py` to observe how the Forward Chaining algorithm works in a rule-based system.

---

## Assignment 7: Implementing the Backward Chaining Algorithm

This assignment demonstrates the use of the Backward Chaining algorithm for reasoning and logical decision-making.

### Problem Overview
Backward Chaining is an inference technique where the algorithm starts with a goal or query and works backward through known rules and facts to prove or disprove it.

### Steps to Run
1. Clone or download the repository.
2. Execute `backward_chaining.py` to see how the Backward Chaining algorithm works in practice.

---

## Assignment 8: Developing a Chatbot Application

This assignment focuses on building a chatbot tailored to address a real-world scenario by engaging in conversations with users.

### Problem Overview
The chatbot is designed to interact with users and provide relevant information or assistance based on a specific use case, utilizing techniques from natural language processing (NLP).

### Technologies Used
- **Natural Language Processing (NLP)**: Enables the chatbot to understand and process user input.
- **Rule-based or Machine Learning-based Chatbot**: The chatbot can either follow predefined rules or leverage machine learning for more dynamic responses.

### Steps to Run
1. Clone or download the repository.
2. Run `chatbot.py` to start interacting with the chatbot.

---

## Assignment 9: Stock Price Prediction Using RNN

This project implements a Recurrent Neural Network (RNN) to predict stock prices based on historical data.

### Overview
The objective of this project is to demonstrate how to use RNNs for time series forecasting. The model utilizes historical closing prices to predict future stock prices for the next 20 days.

### Requirements
Make sure you have the following libraries installed:
- `numpy`
- `pandas`
- `matplotlib`
- `sklearn`
- `keras`

You can install the required packages using pip:
```bash
pip install numpy pandas matplotlib scikit-learn keras
