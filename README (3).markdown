# Knapsack Problem Optimizer

A world-class, interactive web application to visualize the 0/1 Knapsack Problem solved using dynamic programming. Built with Tailwind CSS for a modern, responsive design and JavaScript for solver logic.

## Features
- **Interactive Input**: Add items with weights and values, set knapsack capacity.
- **Dynamic Programming Visualization**: Animated table showing the optimization process.
- **Responsive Design**: Sleek UI with dark/light theme toggle, gradients, and hover effects.
- **Real-Time Feedback**: Info panel shows optimal value and selected items.
- **Clean Code**: Modular JavaScript with clear solver logic.

## Demo
Try it live at [https://your-username.github.io/knapsack-optimizer](https://your-username.github.io/knapsack-optimizer).

![Demo GIF](assets/demo.gif)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/knapsack-optimizer.git
   ```
2. Open `index.html` in a modern browser (no server required).

## Usage
1. Enter weight and value for items, then click "Add Item".
2. Set knapsack capacity and click "Solve" to visualize the dynamic programming process.
3. Use "Clear Items" to reset or "Load Sample" for a test case.
4. Toggle dark/light mode with "Toggle Theme".
5. Watch the table animate and check results in the info panel.

## Tech Stack
- **Frontend**: HTML, JavaScript
- **Styling**: Tailwind CSS (responsive, modern design)
- **Fonts**: Inter (via Tailwind)

## Algorithm Complexity
- Dynamic Programming: O(n * W) where n is the number of items and W is the capacity.
- Space: O(n * W) for the DP table.

## Future Enhancements
- Support fractional knapsack (greedy algorithm).
- Add input validation for large datasets.
- Include export/import for item lists.

## License
MIT License