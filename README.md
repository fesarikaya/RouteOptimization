# Urban Waste Collection Routes Optimization

## Project Overview

This project focuses on optimizing urban waste collection routes using Ant Colony Optimization (ACO). The implementation is done in Python, utilizing graph representations and parallel processing for efficiency. The algorithm achieved a 32.9 km optimum route, resulting in a 15% improvement over manual routing.

## Repository Contents

1. `Urban Waste Collection Routes Optimization.ipynb`: Main Jupyter notebook containing the project code and implementation.
2. `DataSets.ipynb`: Jupyter notebook for generating the datasets used in the project.
3. `traffic_data.csv`: Dataset containing traffic information.
4. `waste_collection_points.csv`: Dataset with information about waste collection points.
5. `urban_road_network.csv`: Dataset representing the urban road network.
6. `Optimization of Urban Waste Collection Routes Using Ant Colony Optimization (ACO).pdf`: Detailed project report.

## Datasets

The project uses three main datasets:

1. **Traffic Data**: Contains information about traffic speed and density for different road segments.
2. **Waste Collection Points**: Includes details about waste collection locations, types, volumes, and collection frequencies.
3. **Urban Road Network**: Represents the road network with nodes, edges, and connectivity information.

## How to Use

1. Clone the repository to your local machine.
2. Ensure you have Jupyter Notebook installed along with the required Python libraries (pandas, numpy, etc.).
3. Open and run the `DataSets.ipynb` notebook to generate the required datasets if needed.
4. Open and run the `Urban Waste Collection Routes Optimization.ipynb` notebook to execute the main project code.

## Key Features

- Implementation of Ant Colony Optimization for route optimization
- Graph representation of the urban road network
- Integration of traffic data for realistic route planning
- Parallel processing for improved efficiency
- Hyperparameter tuning through randomized experiments

## Results

The optimized route achieved a length of 32.9 km, representing a 15% improvement over traditional manual routing methods.

## Future Improvements

- Integration of real-time traffic data for dynamic route optimization
- Incorporation of additional constraints such as vehicle capacity and time windows
- Extension of the algorithm to handle multiple vehicles and depots

## Contributors

Ferhat Sarikaya
