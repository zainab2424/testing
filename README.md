# 🐠 Virtual Aquarium Simulator

This project is a dynamic, interactive virtual aquarium built using the **Processing** IDE. It simulates a vibrant underwater environment complete with autonomous fish agents, a day/night cycle, ambient sound, swaying plants, and user interaction for feeding and predator simulation.

---

## ✨ Features

- **Autonomous Boids Simulation:** Fish agents (Clownfish, Seahorse, Jellyfish, Turtle) exhibit realistic **flocking behaviors** (seek, wander, flee).
- **Interactive Predation:** The mouse cursor acts as a **predator (shark)**, forcing nearby fish to flee.
- **Feeding Mechanic:** Users can **drop food** by clicking, which fish will seek out and consume to replenish their energy.
- **Dynamic Environment:** Features a smooth **day/night cycle**, moving light caustics, bubbles, and static coral clusters.
- **Audio Integration:** Uses the **Minim library** for ambient ocean sounds and subtle bubble sound effects.
- **Dynamic Layout:** The scene dynamically adapts to **window resizing**.

---

## 🛠️ Prerequisites

To run this sketch, you must have the following installed and configured:

1.  **[Processing IDE](https://processing.org/download/)** (Version 3.x or 4.x).
2.  The **Minim Library** for audio.
    * In the Processing IDE, go to **Sketch** > **Import Library** > **Add Library...**
    * Search for **Minim** and click **Install**.
3.  **Audio Files:** The sketch requires two audio files, `ocean.mp3` and `bubbles.mp3`, to be placed in a subfolder named `data` within the sketch's folder.

---

## 🚀 How to Run

1.  **Save the Code:** Save the provided code into a file named `VirtualAquarium.pde`.
2.  **Create Data Folder:** Inside the `VirtualAquarium` sketch folder, create a new subfolder named **`data`**.
3.  **Add Audio:** Place your `ocean.mp3` and `bubbles.mp3` files into the newly created `data` folder.
4.  **Open and Run:**
    * Open the `VirtualAquarium.pde` file in the **Processing IDE**.
    * Click the **Run** button (▶️).

---

## 🎮 Controls

| Key / Action | Function |
| :--- | :--- |
| **Move Mouse** | Controls the position of the **Predator (Shark)**, causing fish to flee. |
| **Mouse Click** | **Drops food** into the water for the fish to eat. |
| **`D`** | Toggles the environment between **Day** and **Night** mode. |
| **`R`** | **Resets** the aquarium: clears all food and re-spawns the initial fish population. |
| **`N`** | **Adds a new fish** agent to the aquarium. |
| **`[`** | **Decreases** the influence radius and strength of the predator. |
| **`]`** | **Increases** the influence radius and strength of the predator. |

---

## 🖼️ Example Output

<img width="1918" height="991" alt="image" src="https://github.com/user-attachments/assets/5e8a5587-07cf-4420-88bc-2e79dfffc6fd" />

