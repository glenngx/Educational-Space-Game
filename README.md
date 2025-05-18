# Space Boy

## Overview
Space Boy is an educational game that takes players on an adventure through the solar system. Players are tasked with navigating through various planets, dodging asteroids and surviving the challenges of each planet while learning fun facts about space. Built with LibGDX, this Java-based game employs object-oriented principles to create an engaging planetary exploration experience.

## Features
- **Planetary Exploration**: Multiple levels based on different planets in the solar system
- **Character Control**: Intuitive movement and jump mechanics for your space explorer
- **Enemy AI**: Face various challenges with sophisticated enemy behavior
- **Dynamic Scenes**: Unique environments and challenges for each planetary level 
- **Sound System**: Immersive background music and sound effects
- **Collision Detection**: Interactive environment with realistic physics

## Project Structure
- **core/**: Contains core game logic and assets
  - **src/**: Source code for the main game class
- **desktop/**: Desktop-specific implementation
  - **src/**: Contains specialized manager packages:
    - **aiControlManager/**: AI behavior systems
    - **collisionManager/**: Collision detection
    - **entityManager/**: Game entities
    - **inputOutputManager/**: Input handling & audio
    - **playerControllerManager/**: Player mechanics
    - **sceneManager/**: Level management and different planetary scenes
    - **simulationLifecycleManager/**: Game lifecycle
- **assets/**: Game resources (images, sounds, etc.)

## Technologies
- **Java**: Core programming language
- **LibGDX**: Game development framework
- **Gradle**: Build system
- **Object-Oriented Design**: Implementing various design patterns

## Installation
1. Clone the repository:
   ```
   git clone https://github.com/glenngx/Space-Boy.git
   ```
2. Ensure you have Java JDK 8+ and Gradle installed
3. Import the project into your preferred IDE (IntelliJ IDEA or Eclipse)
4. Run the desktop launcher:
   ```
   ./gradlew desktop:run
   ```
