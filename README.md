# AGH Space Systems Recruitment Project

This repository contains a Python-based rocket simulation developed for the AGH Space Systems recruitment task. The project models a liquid-propellant rocket and evaluates its key flight characteristics using the RocketPy library.

## Overview

The simulation includes:
- a liquid oxidizer and fuel tank model
- a custom liquid motor configuration
- a rocket geometry with fins and parachutes
- atmospheric environment setup for launch conditions
- aerodynamic drag curves for power-on and power-off phases
- flight analysis for apogee, max velocity, stability margin, and landing speed

## Project files

- `zadanie_rekrutacyjne.py` — main simulation script
- `powerOnDragCurve.csv` — aerodynamic drag data for powered flight
- `powerOffDragCurve.csv` — aerodynamic drag data for coasting flight
- `NACA0012-radians.txt` — airfoil data used for fin geometry

## Requirements

This project depends on `rocketpy` and Python 3.9+.

Install dependencies:

```bash
pip install rocketpy
```

## Run the simulation

```bash
python zadanie_rekrutacyjne.py
```

The script generates the rocket model, runs the flight simulation, prints the mission metrics, and renders the relevant plots.

## Main outputs

The simulation reports:
- apogee altitude
- launch rail departure velocity
- maximum velocity and Mach number
- time to apogee
- parachute deployment and descent behavior
- static stability margin at key flight phases

## Notes

This project was created as a recruitment/engineering exercise and focuses on flight dynamics and conceptual launch vehicle analysis. It is intended for simulation and educational purposes.

## License

This project does not currently include a license file. If you want to publish or share it externally, consider adding an appropriate open-source license.
