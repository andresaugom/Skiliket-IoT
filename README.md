# Skiliket-IoT

An end-to-end IoT platform designed to collect, clean, store, visualize, and model environmental data across urban regions.

## Overview

Skiliket-IoT is a comprehensive IoT system that provides a complete solution for environmental monitoring and data analysis. This project serves as the main hub for documentation and information about the entire system, which consists of two main components:

1. **Data Collection & Processing (Raspberry Pi)** - [Skiliket-RPI4](https://github.com/andresaugom/Skiliket-RPI4)
2. **Data Visualization & Dashboard** - [Skiliket-Dashboard](https://github.com/andresaugom/Skiliket-Dashboard)

## System Architecture

The Skiliket-IoT system is built with a distributed architecture that separates data collection from data visualization:

```
[IoT Sensors] → [Raspberry Pi 4] → [Data Storage] → [Dashboard Application]
```

### Components

#### 1. Skiliket-RPI4 (Data Collection & Processing)
**Repository:** [github.com/andresaugom/Skiliket-RPI4](https://github.com/andresaugom/Skiliket-RPI4)

The Raspberry Pi component is responsible for:
- **Data Collection**: Gathering environmental data from connected IoT sensors
- **Data Processing**: Cleaning and preprocessing sensor data
- **Data Transmission**: Sending processed data to storage systems
- **Edge Computing**: Performing initial data analysis at the edge

#### 2. Skiliket-Dashboard (Visualization & Analysis)
**Repository:** [github.com/andresaugom/Skiliket-Dashboard](https://github.com/andresaugom/Skiliket-Dashboard)

The dashboard component provides:
- **Data Visualization**: Interactive charts and graphs for environmental data
- **Real-time Monitoring**: Live updates of sensor readings
- **Historical Analysis**: Access to historical data and trends
- **User Interface**: Web-based interface for system management and monitoring

## Features

- **End-to-End Solution**: Complete pipeline from data collection to visualization
- **Scalable Architecture**: Designed to support multiple sensors and data sources
- **Real-time Processing**: Live data streaming and updates
- **Environmental Monitoring**: Track temperature, humidity, air quality, and other environmental parameters
- **Data Storage**: Persistent storage for historical data analysis
- **Web-Based Interface**: Access your data from anywhere

## Getting Started

To set up the complete Skiliket-IoT system:

1. **Set up the Raspberry Pi component**:
   - Visit [Skiliket-RPI4](https://github.com/andresaugom/Skiliket-RPI4) for installation instructions
   - Configure your IoT sensors
   - Set up data collection scripts

2. **Set up the Dashboard**:
   - Visit [Skiliket-Dashboard](https://github.com/andresaugom/Skiliket-Dashboard) for installation instructions
   - Configure data source connections
   - Customize visualizations

## Use Cases

- **Urban Environmental Monitoring**: Track air quality and weather conditions across cities
- **Smart Buildings**: Monitor indoor environmental conditions
- **Agriculture**: Track environmental parameters for optimal crop growth
- **Research**: Collect and analyze environmental data for scientific studies

## Contributing

This is a project repository that serves as documentation for the Skiliket-IoT system. For specific contributions:
- For data collection features, visit [Skiliket-RPI4](https://github.com/andresaugom/Skiliket-RPI4)
- For dashboard features, visit [Skiliket-Dashboard](https://github.com/andresaugom/Skiliket-Dashboard)

## License

Please refer to the individual component repositories for license information.

## Contact

For questions or support, please open an issue in the relevant repository:
- [Skiliket-RPI4 Issues](https://github.com/andresaugom/Skiliket-RPI4/issues)
- [Skiliket-Dashboard Issues](https://github.com/andresaugom/Skiliket-Dashboard/issues)
