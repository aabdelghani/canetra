# CANetra: Multi-node CAN Debugger

## Overview
CANetra is a sophisticated tool designed for debugging and monitoring multi-node Controller Area Network (CAN) setups, specifically tailored for the STM32 Nucleo-F303RE microcontroller. This project aims to provide a comprehensive platform for automotive engineers and developers working with CAN networks, facilitating real-time network traffic analysis, diagnostics, and effective message logging.

## Features
- **Real-Time CAN Network Monitoring**: Visualize and analyze traffic on CAN networks in real-time.
- **Advanced Diagnostics**: Perform diagnostics on multiple nodes, identifying network errors and issues.
- **Efficient Message Logging**: Record, store, and analyze CAN messages for in-depth examination.
- **STM32 Nucleo-F303RE Compatibility**: Custom-built for compatibility with the STM32 Nucleo-F303RE platform.
- **Intuitive User Interface**: Easy-to-use interface for efficient monitoring and debugging.
- **Data Export and Analysis**: Export recorded data for further analysis.

## Getting Started

### Prerequisites
- STM32 Nucleo-F303RE board
- SN65HVD230 CAN Bus Transceiver Module
- Software requirements (e.g., STM32CubeIDE, appropriate drivers)

### Installation
**1. Clone the repository**:
git clone https://github.com/aabdelghani/CANetra.git
**2. Setup the Development Environment**:
- Install STM32CubeIDE and configure it for the Nucleo-F303RE board.
- Install Qt 5.x and set up the development environment for GUI development.
- Set up the necessary drivers for the SN65HVD230 CAN transceiver module.

**3. Load and Configure the Firmware**:
- Open the firmware project in STM32CubeIDE.
- Build and flash the firmware to the Nucleo-F303RE board.

**4. Develop the Qt Application**:
- Open the Qt project in Qt Creator.
- Compile and build the application.

**5. Connect the Hardware**:
- Attach the SN65HVD230 CAN transceiver to the Nucleo-F303RE.
- Ensure proper connections to the CAN network.

## Usage
1. Power on the Nucleo-F303RE with the connected SN65HVD230 CAN module.
2. Launch the CANetra Qt application on your computer.
3. Configure the connection settings to communicate with the Nucleo board.
4. Start monitoring the CAN network and use the provided GUI tools for debugging.

## Documentation
For detailed documentation, refer to the `docs` directory within the repository.

## Contributing
Contributions to CANetra are welcome! Please read the [Contributing Guidelines](CONTRIBUTING.md) for details on submitting pull requests and reporting issues.

## License
This project is licensed under the [MIT License](LICENSE) - see the LICENSE file for details.

## Support
For support and queries, please open an issue in the GitHub repository or contact [Support Email].

## Acknowledgements
Special thanks to the contributors and supporters who have made CANetra possible, especially those in the STM32, CAN network, and Qt development communities.
