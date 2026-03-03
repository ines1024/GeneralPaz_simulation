# General Paz Traffic Simulation

**Stochastic Traffic Modeling | Statistical Simulation | Python**

A stochastic simulation of traffic flow on a 15 km highway segment
inspired by Avenida General Paz (Buenos Aires).

This project models vehicle dynamics, congestion, collisions, and speed
control mechanisms using probabilistic methods and event-driven
simulation.

------------------------------------------------------------------------

##  Objective

To model highway traffic as a **time-dependent stochastic system**,
where:

-   Vehicle speeds follow probability distributions\
-   Arrival rates vary by time of day (peak vs off-peak)\
-   Vehicle interactions generate congestion and collisions\
-   Speed violations are detected at fixed control points\
-   Statistical metrics are collected for analysis

The simulation runs over a full 24-hour cycle and exports aggregated
results.

------------------------------------------------------------------------

##  Modeling Highlights

-   Microscopic vehicle-based simulation\
-   Normally distributed speeds (peak/off-peak regimes)\
-   State-dependent acceleration logic\
-   Endogenous collision generation\
-   Speed camera enforcement system\
-   Hourly statistical aggregation

This system can be interpreted as a **discrete-time stochastic dynamic
process** with state-dependent transitions.

------------------------------------------------------------------------

##  Collected Metrics

-   Vehicle count per hour\
-   Average travel time\
-   Average speed\
-   Collision count\
-   Fine count\
-   Speed distribution at checkpoints

Results are exported to CSV for further statistical analysis and
visualization.

------------------------------------------------------------------------

## Project Structure

    main.py                  # Simulation engine & visualization
    class_specification.py   # Vehicle (Auto) and Lane (Carril) models
    data.py                  # Data aggregation & export
    plots.py                 # Statistical visualization
    simulaciones.csv         # Output dataset
    media/                   # Assets (images & audio)
    resultados/              # Generated results

------------------------------------------------------------------------

## Technologies

-   Python\
-   Pygame (visual simulation)\
-   Matplotlib (analysis & plots)\
-   CSV (data export)

------------------------------------------------------------------------

## Why This Project

This project demonstrates:

-   Applied stochastic modeling\
-   Dynamic systems simulation\
-   Event-driven architecture\
-   Statistical data pipeline design\
-   Real-world system abstraction

It reflects the power of combining probability, simulation, and data
analysis to model complex systems.
