# Wumpus World

Wumpus World is a classic AI problem used to demonstrate various concepts in logic, search algorithms, and agent-based systems. This project provides a simulation of the Wumpus World environment and an intelligent agent that navigates the world to find gold while avoiding pits and the Wumpus. This implementation uses Angular for the frontend and Spring Boot for the backend.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Architecture](#architecture)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)

## Introduction
Wumpus World is a 4x4 grid-based environment containing:
- A Wumpus that the agent must avoid.
- Pits that the agent must avoid falling into.
- Gold that the agent must find and retrieve.
- Walls that form the boundaries of the grid.

The agent starts in the bottom-left corner of the grid and uses its sensors (stench, breeze, glitter, bump, and scream) to navigate the world.

## Features
- **Grid-based environment**: A customizable 4x4 grid representing the Wumpus World.
- **Intelligent agent**: An AI agent that uses logic and search algorithms to find the gold and avoid hazards.
- **Sensors**: Simulated sensors that provide percepts like stench, breeze, glitter, bump, and scream.
- **Visualization**: A graphical representation of the Wumpus World environment and the agent's actions using Angular.

## Architecture
This project follows a client-server architecture:
- **Frontend**: Developed using Angular. It provides a user interface for visualizing the Wumpus World and interacting with the simulation.
- **Backend**: Developed using Spring Boot. It handles the game logic, state management, and communication with the frontend.
