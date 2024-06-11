# Dyna-Q Simulation

This repository contains MATLAB code for simulating the Dyna-Q reinforcement learning algorithm. Dyna-Q is a model-based reinforcement learning algorithm that combines learning, planning, and acting by integrating model-free and model-based approaches.

## Contents

- **[CreateGrid.m](CreateGrid.m)**: MATLAB script for creating the grid environment for the Dyna-Q simulation.
- **[NNModel_Dyna.m](NNModel_Dyna.m)**: Neural network model used in the Dyna-Q simulation.
- **[ParseArrows.m](ParseArrows.m)**: Script for parsing and visualizing the policy arrows.
- **[ParseArrows2.m](ParseArrows2.m)**: Another script variation for parsing and visualizing the policy arrows.
- **[mainAlgo_Dyna_Q_Wall_NewModel_Loop.m](mainAlgo_Dyna_Q_Wall_NewModel_Loop.m)**: Main script implementing the Dyna-Q algorithm with a wall obstacle and loop.

## Getting Started

### Prerequisites

- MATLAB (for running the `.m` files)

### Usage

1. Clone the repository:
    ```bash
    git clone https://github.com/mincasurong/DynaQ.git
    cd DynaQ
    ```

2. Open the desired `.m` file in MATLAB and run it to execute the Dyna-Q simulation.

### Example

To run the main Dyna-Q algorithm:
1. Open `mainAlgo_Dyna_Q_Wall_NewModel_Loop.m` in MATLAB.
2. Run the script to observe the behavior of the Dyna-Q algorithm in the grid environment.

## Dyna-Q Algorithm

Dyna-Q combines model-free Q-learning with model-based planning. It uses the learned model to simulate experiences and update the Q-values, improving learning efficiency.

### Key Features

- **Model-Based Planning**: Integrates simulated experiences to update Q-values.
- **Neural Network Model**: Uses a neural network to approximate the Q-values.
- **Obstacle Handling**: Includes handling of wall obstacles in the environment.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any improvements or additions.

## Acknowledgements

Special thanks to the contributors and the MATLAB community for their continuous support and resources.
