# **RoboRally**

**RoboRally** is a strategy-based game developed in **C++** that combines engaging gameplay mechanics with advanced Object-Oriented Programming (OOP) principles. Designed as a university project, the game emphasizes both coding excellence and user interaction through a graphical interface.

---

## **Table of Contents**
- [Introduction](#introduction)
- [Features](#features)
- [Game Modes](#game-modes)
- [Technologies Used](#technologies-used)
- [Setup and Installation](#setup-and-installation)
- [How to Play](#how-to-play)
- [Contributions](#contributions)
- [License](#license)

---

## **Introduction**

RoboRally is a two-player game where robots navigate a grid filled with **boosters**, **obstacles**, and strategic elements. Players aim to reach a **flag cell** before their opponent by choosing movement commands, using power-ups, and avoiding dangers. The game showcases the integration of **OOP principles** and **GUI-based interaction**, creating a fun and educational experience.

---

## **Features**

- **Two Game Modes**:
  - **Design Mode**: Customize the game grid by adding objects like flags, belts, danger zones, water pits, and more.
  - **Play Mode**: Compete against another player to reach the flag while interacting with game objects and using strategic moves.
- **Grid Mechanics**:
  - Supports a 5x11 grid with numbered cells (1-55).
  - Game objects include flags, belts, danger zones, workshops, antennas, water pits, and rotating gears.
- **Player Interactions**:
  - Health-based command system: Players with higher health can execute more moves per turn.
  - Strategic shooting phase: Robots fire lasers at each other in the same row or column.
  - Workshop upgrades: Purchase weapons, consumables, and devices like lasers or shields.
- **Graphics**:
  - GUI-based interaction with toolbars, command bars, and status updates.
  - Visual representation of players, grid objects, and commands.

---

## **Game Modes**

### **1. Design Mode**
- Add, edit, or remove game objects on the grid.
- Save and load grid configurations for future use.
- Supported objects:
  - **Flag**: Destination cell for the game.
  - **Belts**: Move robots between cells.
  - **Water Pits**: Instantly destroy robots.
  - **Danger Zones**: Reduce robot health.
  - **Workshops**: Repair robots and purchase upgrades.
  - **Rotating Gears**: Rotate robots by 90°.

### **2. Play Mode**
- Players navigate their robots on the grid using movement commands:
  - **Move Forward**, **Move Backward**, **Rotate Left**, **Rotate Right**.
- Commands are randomly generated and limited by player health.
- Robots interact with grid objects during movement and engage in strategic battles.

---

## **Technologies Used**

- **Programming Language**: C++
- **Development Paradigm**: Object-Oriented Programming (OOP)
- **Graphics Library**: Custom GUI framework for graphical interaction

---

## **Setup and Installation**

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/AliIbrahim174/roborally.git

   ## **Build the Project**

- Open the project in a C++ IDE (e.g., Visual Studio or Code::Blocks).
- Build the project to ensure all dependencies are resolved.

## **Run the Application**

- Execute the built application to start the game.

---

## **How to Play**

### **In Design Mode**
- Use the toolbar to add objects to the grid.
- Save and load grid configurations for future use.

### **In Play Mode**
1. Select movement commands based on health.
2. Navigate the grid and interact with objects.
3. Use consumables or workshop upgrades to gain an advantage.
4. Be the first to reach the flag cell to win!

---

## **Contributions**

This project was developed as part of the **CMPS102 Programming Techniques** course at Cairo University. Team members collaborated on various aspects, including game design, GUI development, and core functionality implementation.

---

## **License**

This project is open-source and available under the [MIT License](LICENSE).

