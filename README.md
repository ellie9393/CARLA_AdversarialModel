# CARLA_AdversarialModel

## Overview
This project explores the impact of noise on agent behaviors in the CARLA simulator. The focus is on analyzing how different types of noise affect decision-making, waypoint following, tailgating behavior, and collision management. By introducing controlled noise, we can evaluate the robustness of autonomous agents in simulated environments.

## Installation and Setup
To get started, follow this [(https://www.youtube.com/watch?v=jIK9sanumuU)] to install CARLA and set up the environment.

### Prerequisites
- Python
- CARLA
- Required dependencies:
  

## Repository Structure
This repository contains the following directories:

- **`Nosiy_waypoints`**: Implements noisy waypoint following behavior where agents deviate from their intended path.
- **`Noisy_waypoints_increasing`**: Similar to `Nosiy_waypoints`, but with progressively increasing noise levels.
- **`reckless_agent`**: Introduces reckless driving behaviors such as aggressive lane changes and high-speed maneuvers.
- **`tailgating_behavior`**: Implements tailgating agents to analyze proximity-based decision-making.
- **`collison_manager_behavior`**: Modifies collision handling mechanisms to evaluate how agents react to unexpected obstacles.

## Running the Simulations
To execute any scenario, navigate to the corresponding folder and run the script. 


## Data Collection and Analysis
- The project logs key metrics such as average speed, number of collisions, and deviations from intended waypoints.
- Results are stored in CSV files for further analysis.
- Visualizations and comparisons of noisy vs. base behaviors are provided.

## Contributions and Future Work
- Contributions are welcome! Please submit a pull request or open an issue.
- Future improvements include:
  - Adding more complex noise types.
  - Integrating machine learning models for adaptive noise resistance.
  - 

## License and Acknowledgments
This project is open-source and available under the MIT License. Special thanks to the CARLA team and the open-source community for providing valuable tools for autonomous driving research.


 
