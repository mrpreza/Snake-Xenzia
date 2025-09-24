# Snake-Xenzia
FPGA implementation of the classic Snake game using VHDL, featuring real-time VGA output, snake movement, food generation, and collision detection — built and simulated with Xilinx ISE. 
It uses a **VGA controller** to render the game on a monitor and basic logic for snake movement, food generation, and collision detection.

---

## 📂 Project Structure
- **`CADproj.vhd`** – Main top-level VHDL design file.
- **`VGA_controller.vhd`** – Handles VGA timing signals for display output.
- **`VGA_Square.vhd`** – Module for rendering game elements (snake segments, food) as colored blocks.
- **`.xise`, `.gise`** – Xilinx ISE project configuration files.
- **Generated files (`.bit`, `.ngc`, `.ncd`, `.xrpt`, etc.)** – Build artifacts from synthesis and implementation.

---

## 🛠 Requirements
- **Xilinx ISE** (tested with ISE Design Suite)
- Supported FPGA development board (e.g., Spartan-3, Spartan-6, or compatible)
- VGA-compatible monitor

---

## 🚀 How to Run
1. Open the project in **Xilinx ISE** using `Snake.xise`.
2. Synthesize, implement, and generate the bitstream (`.bit` file).
3. Program your FPGA board with the generated bitstream.
4. Connect a **VGA monitor** to the FPGA board.
5. Use board inputs (buttons/switches) to control the snake.

---

## 🎮 Features
- Real-time Snake game running entirely in hardware logic.
- VGA video output.
- Snake grows when it eats food.
- Game ends on collision with walls or itself.

---

## 📖 Notes
- This project is for educational purposes to demonstrate **digital design** and **FPGA programming**.
- Modify the VHDL files to adapt the game resolution, snake speed, or board-specific pin assignments.

---

## 📜 License
This project is open-source and available under the MIT License.
