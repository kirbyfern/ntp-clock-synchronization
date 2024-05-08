# SimGrid NTP Simulation Project

## Overview

This project demonstrates a simple implementation of the Network Time Protocol (NTP) using the SimGrid framework. It simulates a distributed system where a master node synchronizes its clock with worker nodes to ensure time consistency across the network. The simulation is designed to run in a distributed environment, showcasing the synchronization process between a server (master) and clients (workers).

## Getting Started

### Prerequisites

- Python 3.x
- SimGrid

### Installation

1. Install SimGrid:
  pip3 install simgrid

2. Clone the repository:
  git clone https://github.com/yourusername/simgrid-ntp-simulation.git cd simgrid-ntp-simulation

3. Install the project dependencies:
  pip install -r requirements.txt

### Running the Simulation

To run the simulation, execute the following command:
  python berkeley_simulation.py platform.xml deployment.xml

Ensure you have the `platform.xml` and `deployment.xml` files in the project directory. These files define the simulation environment, including the hosts and actors involved.

## Project Structure

- `berkeley_simulation.py`: The main script that runs the simulation.
- `platform.xml`: Defines the simulation platform, including hosts and their properties.
- `deployment.xml`: Specifies the deployment of actors (master and workers) on the platform.

## Contributing

Contributions are welcome! Please read the [CONTRIBUTING.md](CONTRIBUTING.md) for details on how to contribute to this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

- SimGrid for providing the simulation framework.
- The NTP protocol for inspiring this simulation.

## Contact

For any questions or feedback, please contact the project maintainer