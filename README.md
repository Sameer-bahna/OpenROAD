# 7nm-PHYSICAL-DESIGN-CONTEST-USING-OPENROAD
This repository gives brief review of Physical Design of RISC-V processor core using 7nm ASAP7 PDK. 

# OpenROAD EDA Tool
OpenROAD is an integrated chip physical design tool that takes a design from synthesized Verilog to routed layout.

• An outline of steps used to build a chip using OpenROAD is shown below:

• Initialize floorplan - define the chip size and cell rows

• Place pins (for designs without pads )

• Place macro cells (RAMs, embedded macros)

• Insert substrate tap cells

• Insert power distribution network

• Macro Placement of macro cells

• Global placement of standard cells

• Repair max slew, max capacitance, and max fanout violations and long wires

• Clock tree synthesis

• Optimize setup/hold timing

• Insert fill cells

• Global routing (route guides for detailed routing)

• Antenna repair

• Detailed routing

• Parasitic extraction

• Static timing analysis

OpenROAD uses the OpenDB database and OpenSTA for static timing analysis.
              
              
# Proposed Methods to Improve fmax 

  1) Replacing RVT Cells by LVT Cell & using FF Library
  2) Modification in Placement Density
  3) Modification with Autotuner
  

# Final Layout



The design ensures 0 DRC violations


![image](https://user-images.githubusercontent.com/128247536/228820156-b78db6ec-83de-4a99-92b4-1b4e2f061201.png)

![Screenshot (73)](https://user-images.githubusercontent.com/128247536/228819245-2e0e3bab-8d91-4fdc-b5aa-a0f5fbca2d3b.png)

# Results

The final modified design constraints are given as follows :

              ⇒   Minimum Clock Period      :   1613.75 ps
              ⇒   Maximum Clock Frequency   :   619.75 MHz
              ⇒   Design Area               :   2490 u^2
              ⇒   Power                     :   12.1 mW
              

# Acknowledgements

1.	Kunal Ghosh (Co-Founder, VLSI System Design Pvt. Ltd.)
	
2.	Sumanto Kar (Sr. Project Technical Assistant, IIT Bombay)

3.  Vijayan Krishnan

# Contact Details

Mr. Sameer Bahna

Mail : sameer.kha9039@gmail.com
