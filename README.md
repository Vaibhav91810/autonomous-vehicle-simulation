# Autonomous Vehicle Simulation

## Project Overview

This project aims to develop a simulation environment to test autonomous vehicles. The simulation will include various scenarios like pedestrian crossings, traffic signals, and lane changes to validate the vehicle's decision-making process and safety protocols.

## Features

- **Traffic Signal Simulation**: Implement traffic lights and their behavior.
- **Pedestrian Crossing**: Simulate pedestrian crossings at various points.
- **Lane Change Scenarios**: Test the vehicle's ability to change lanes safely.
- **Obstacle Detection**: Detect and respond to obstacles.
- **Weather Conditions**: Simulate different weather conditions and their impact on the vehicle's performance.

## Technologies Used

- **Programming Language**: Python
- **Simulation Engine**: CARLA Simulator
- **Machine Learning**: TensorFlow/PyTorch
- **Visualization**: Matplotlib, OpenCV

## Setup and Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Vaibhav91810/autonomous-vehicle-simulation.git
   cd autonomous-vehicle-simulation
   ```

2. Set up the virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Download and set up the CARLA simulator from [CARLA's official website](https://carla.org/).

## Usage

1. Start the CARLA simulator.
2. Run the simulation script:
   ```bash
   python run_simulation.py
   ```

## Project Structure

```plaintext
autonomous-vehicle-simulation/
│
├── data/
│   ├── scenarios/
│   └── models/
│
├── src/
│   ├── traffic_signal.py
│   ├── pedestrian_crossing.py
│   ├── lane_change.py
│   ├── obstacle_detection.py
│   ├── weather_conditions.py
│   ├── vehicle_controller.py
│   └── simulation_manager.py
│
├── tests/
│   ├── test_traffic_signal.py
│   ├── test_pedestrian_crossing.py
│   ├── test_lane_change.py
│   ├── test_obstacle_detection.py
│   ├── test_weather_conditions.py
│   └── test_vehicle_controller.py
│
├── requirements.txt
├── run_simulation.py
└── README.md
```

## Contributing

Contributions are welcome! Please read the [contributing guidelines](CONTRIBUTING.md) first.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
