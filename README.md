# Virtual Aquarium
This project is an **interactive, real-time underwater simulation** built using the **Processing IDE**. It models an underwater environment populated by multiple species of animated sea creatures, coral clusters, bubbles, and plants.

The simulation features autonomous fish with various behaviors, including wandering, searching for food, and fleeing from a user-controlled predator.

---

## Key Features
* **Multi-species Fish**: Includes clownfish, seahorses, jellyfish, and turtles.
* **Interactive Feeding**: Click to drop food particles that fish detect and seek out to replenish their energy.
* **Predator-Following Shark Cursor**: The mouse cursor is represented as a shark, and its presence dynamically influences fish behavior within its fear radius. The strength of the fleeing force increases the closer a fish is to the shark.
* **Dynamic Day/Night Toggle**: Press 'D' to smoothly switch between day and night modes.
* **Visual Realism**: Features realistic coral, rising bubbles, a water gradient, and rippling **caustics background effect** (shimmering light rays) using Perlin noise and dynamic color interpolation.
* **Audio Integration**: Continuous ambient ocean waves and bubble sounds are layered with a fun pirate soundtrack using the **Minim library**.
* **Fish Energy System**: Each fish has an **energy bar** that drains over time (causing them to slow down) and replenishes when food is consumed. The bar transitions from green (high energy) to red (low energy).

---

## How to Run
1.  **Open** `VirtualAquarium.pde` in the **Processing IDE**.
2.  **Ensure the required folder structure exists** with the sound files in the `data/` folder:
    ```
    VirtualAquarium/
    ├── VirtualAquarium.pde
    └── data/
        ├── ocean.mp3
        └── bubbles.mp3
    ```
3.  Click **Run** in Processing.

---

## Controls
| Control | Action |
| :--- | :--- |
| **Mouse Click** | Drop food particles |
| **Move Mouse** | Control predator (shark) cursor |
| **D** | Toggle day/night |
| **R** | Reset aquarium |
| **N** | Add new fish |
| **[ → smaller** | Adjust predator size (fear radius) |
| **] → bigger** | Adjust predator size (fear radius) |

---

## Example Output
Below are visual examples of the simulation in day and nigh mode:
<img width="1918" height="991" alt="image" src="https://github.com/user-attachments/assets/5e8a5587-07cf-4420-88bc-2e79dfffc6fd" />

