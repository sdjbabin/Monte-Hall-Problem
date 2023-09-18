# Monty Hall Problem Simulation

This Python script simulates the famous Monty Hall problem, a probability puzzle named after the host of the television game show "Let's Make a Deal," Monty Hall. The problem illustrates the concept of conditional probability and challenges common intuition regarding decision-making under uncertainty.

## Description

In the Monty Hall problem, a player is presented with three doors. Behind one of the doors is a valuable prize (e.g., a car), while the other two doors conceal undesirable items (e.g., goats). The player makes an initial choice, selecting one of the doors. 

The host, who knows what is behind each door, then reveals one of the other two doors with a goat behind it. At this point, the player has a decision to make:

- **Switch Strategy:** The player can choose to switch to the remaining unopened door.
- **Stay Strategy:** The player can choose to stick with their initial choice.

The goal of this simulation is to compare the win percentages of these two strategies over a large number of simulated games. The result often surprises people: the "Switch Strategy" has a higher probability of winning the valuable prize compared to the "Stay Strategy."

## Simulation Details

- The simulation runs a specified number of rounds, each representing one game of the Monty Hall problem.
- In each round, the doors are randomized to hide the prize and goats.
- The player's initial choice is also randomized.
- The host, following the rules of the Monty Hall problem, reveals a door with a goat behind it.
- Depending on the player's chosen strategy (switch or stay), the final choice is determined.
- The simulation tracks the win percentage for both strategies.

## How to Run

1. Ensure you have Python installed on your computer.
2. Install the required libraries (NumPy and Matplotlib) if you haven't already:

    ```
    pip install numpy matplotlib
    ```

3. Run the `monty_hall_simulation.py` script.

## Results

The script will display a bar chart illustrating the win percentages for the "Switch Strategy" and the "Stay Strategy" based on the specified number of simulations.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

[Soham Chatterjee]

Feel free to modify and share this simulation as an educational tool or a fun probability demonstration!
