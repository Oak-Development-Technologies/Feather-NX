# Hardware Files for Feather NX

Feather NX is a Lattice Semiconductor based FPGA Feather Board using the Crosslink-NX LIFCL-40-7BG256I Crosslink-NX FPGA. The board features an FT232H to operate as a JTAG host in which you can program the FPGA bitstream. 

No high speed SERDES are broken out.

DPHY0 is broken out completely to a Raspberry Pi 22 Pin compatible 4 lane MIPI FPC connector. Due to manufacturing constraints and costs, manufacturing on a standard 6L service from JLCPCB will only yield between 64 and 67 ohms of
differential impedance, or around 32 ohms single ended impedance.

Additionally, 4 pairs of differential length matched traces are broken on the longer edge of the board next to the 4 available analog pins on the FPGA. These should have approximate differential impedance of between 64 and 67 ohms.

The remaining pins on the other side are differentially routed but not length matched with similar expected impedance characteristics.
