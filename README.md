# Virtual Aquarium
[cite_start]This project is an **interactive, real-time underwater simulation** built using the **Processing IDE**[cite: 12]. [cite_start]It models an underwater environment populated by multiple species of animated sea creatures, coral clusters, bubbles, and plants[cite: 13].

[cite_start]The simulation features autonomous fish with various behaviors, including wandering, searching for food, and fleeing from a user-controlled predator[cite: 14].

---

## Key Features
* [cite_start]**Multi-species Fish**: Includes clownfish, seahorses, jellyfish, and turtles[cite: 17].
* [cite_start]**Interactive Feeding**: Click to drop food particles [cite: 18] [cite_start]that fish detect and seek out to replenish their energy[cite: 89, 21].
* [cite_start]**Predator-Following Shark Cursor**: The mouse cursor is represented as a shark, and its presence dynamically influences fish behavior within its fear radius[cite: 14, 93]. [cite_start]The strength of the fleeing force increases the closer a fish is to the shark[cite: 94, 98].
* [cite_start]**Dynamic Day/Night Toggle**: Press 'D' to smoothly switch between day and night modes[cite: 19, 70].
* [cite_start]**Visual Realism**: Features realistic coral, rising bubbles, a water gradient, and rippling **caustics background effect** (shimmering light rays) [cite: 20] [cite_start]using Perlin noise and dynamic color interpolation[cite: 35].
* [cite_start]**Audio Integration**: Continuous ambient ocean waves and bubble sounds [cite: 20] [cite_start]are layered with a fun pirate soundtrack using the **Minim library**[cite: 15, 130].
* [cite_start]**Fish Energy System**: Each fish has an **energy bar** that drains over time (causing them to slow down) and replenishes when food is consumed[cite: 21, 144, 145]. [cite_start]The bar transitions from green (high energy) to red (low energy)[cite: 146].

---

## How to Run
1.  [cite_start]**Open** `VirtualAquarium.pde` in the **Processing IDE**[cite: 23].
2.  [cite_start]**Ensure the required folder structure exists** with the sound files in the `data/` folder[cite: 23]:
    ```
    VirtualAquarium/
    [cite_start]├── VirtualAquarium.pde [cite: 25]
    [cite_start]└── data/ [cite: 26]
        [cite_start]├── ocean.mp3 [cite: 27]
        [cite_start]└── bubbles.mp3 [cite: 28]
    ```
3.  [cite_start]Click **Run** in Processing[cite: 29].

---

## Controls
| Control | Action |
| :--- | :--- |
| **Mouse Click** | [cite_start]Drop food particles [cite: 30] |
| **Move Mouse** | [cite_start]Control predator (shark) cursor [cite: 30] |
| **D** | [cite_start]Toggle day/night [cite: 30] |
| **R** | [cite_start]Reset aquarium [cite: 30] |
| **N** | [cite_start]Add new fish [cite: 30] |
| **[ → smaller** | [cite_start]Adjust predator size (fear radius) [cite: 30] |
| **] → bigger** | [cite_start]Adjust predator size (fear radius) [cite: 30] |

---

## Example Output
Below is a visual example of the simulation:

<img width="1918" height="991" alt="image" src="https://github.com/user-attachments/assets/5e8a5587-07cf-4420-88bc-2e79dfffc6fd" />

