# PurpleAir Longevity Algorithm Project

## Overview
This project analyzes long-term drift in PurpleAir PM2.5 sensors and develops a correction model that adjusts readings based on sensor age, humidity, temperature, and other environmental factors.

## Goals
- Quantify long-term accuracy decline in PurpleAir sensors.
- Compare PurpleAir data with nearby EPA regulatory monitors.
- Extend the Barkjohn–Gantt–Clements (2021) correction model by adding a "longevity" term.
- Build a regression or ML-based drift model.
- Produce an open-source correction formula and validation results.

## Repository Structure
/data              → raw PurpleAir + EPA datasets (or placeholders)
/notebooks         → weekly Jupyter notebooks
/sketches          → pipeline diagrams and design notes
/scripts           → final analysis scripts

