# Laser Puzzle Generator

https://tigerlordz99.github.io/MidtermLaser/

A tool for creating solvable laser reflection puzzles. This generator is built specifically for level designers to prototype gameplay layouts.

## **What it Generates**
The tool procedurally builds 2D puzzle blueprints including:
* **Green Emitter**: The laser source (always on the left).
* **Red Goal**: The target destination (always on the right).
* **Mirrors**: Angular surfaces that reflect light at 90-degree turns.
* **Obstacles**: Solid grey blocks that create narrow corridors and block paths.



## **Access & Controls**
1. **Direct Link**: Open the hosted GitHub Pages link above.
2. **Local Run**: Download `index.html` and open it in any web browser.
3. **Controls**: Use the **Sliders** to adjust difficulty and **Generate New** to create a fresh puzzle.

## **Parameters**
* **Map Size (6–10)**: Sets the grid resolution. Small maps are harder to navigate with many mirrors.
* **Mirrors (1–10)**: The exact number of reflections required to hit the goal. Higher counts increase logical complexity.
* **Obstacles (0–20)**: Adds visual noise. Obstacles are strategically placed near the correct path to hide the solution.
* **Puzzle Seed**: A unique 6-digit code. Share seeds with others to play the exact same map layout.

## **Example Outputs and Feedback Proof**
* https://docs.google.com/document/d/1rzT8RNh3GK583om77L77L1S0XmiUCNEvqaSLHghSD40/edit?usp=sharing

## **Known Limitations**
* **Self-Crossing Path**: The laser is allowed to cross itself. On small maps, this can look cluttered.
* **Emitter Collisions**: The laser cannot bounce directly back into the Emitter (it acts as a solid block).
* **Single Solution**: While other solutions might exist, the tool only verifies and displays the primary generated path.

## **AI Disclaimer**
* I utilized generative AI tools to help develop the code and README, and mainly used them to convert from a Unity application to a web application.
