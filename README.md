# Collision_Avoidance_System_RTL_TO_GDS
Designed Verilog RTL for a collision avoidance system and executed a complete RTL-to-GDSII flow using Cadence Genus (synthesis) and Innovus (P&amp;R) in 65nm technology. Achieved timing closure and verified functional equivalence using Conformal Equivalence Checking (CEC). Managed floorplanning, placement, and routing to produce a DRC/LVS clean GDSII 
# Collision Avoidance Car (CAC) Controller: RTL-to-GDSII Implementation Flow

Designed and implemented a fully digital hardware controller acting as the "brain" of an autonomous self-driving vehicle[cite: 1]. The system processes real-time sensor streams and implements a complex state machine to handle speed acceleration, highway cruising, automatic lane-changing maneuvers for overtaking, and emergency obstacle breaking[cite: 1]. 

The execution spans the entire digital VLSI backend flow: from synthesizable Verilog RTL creation and high-coverage testbench verification down to logic synthesis optimization, DFT scan chain insertion, formal equivalence checks, Static Timing Analysis (STA), and full physical design placement and routing (P&R) to deliver a tape-out ready GDSII stream[cite: 1, 2].

---

## 📂 Repository Directory Structure

```text
├── rtl/             # Synthesizable Verilog HDL design source code files
├── sim/             # Exhaustive code-coverage simulation testbenches (SimVision)
├── scripts/         # Automation constraints and tool run scripts (SDC, Tcl, LEC Do-files)
└── docs/            # Full technical project reports, FSM diagrams, and layout screen captures
