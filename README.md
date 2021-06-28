# ZoRAM - Eight Megabyte Fast RAM Expansion for the Amiga 2000

This project does not work at this time. Build at your own risk.

I have always felt big box Amiga's should be used as intended. Expansion should be targeted to the expansion slots provided. This project aims to provde an 8 megabyte expansion option via the Zorro II bus of the Amiga 2000. Based on LIV2's GottaGoFastRAM for 68000 DIP based Amigas. Due to the relative messiness of the  data and address line locations on the Zorro II connector, it was necessary to  change the connection points on the Xilinx. As such, the JED file for this project is specific to this project and cannot be interchanged with LIV2's original.

![ZoRAM Image](ZoRAM.jpg)


# PCB Ordering and Assembly

Under construction

# Programming the CPLD

To be completed later.

# BOM

|Component|Package|Location|QTY|Source|Part Number|
--- | --- | --- | --- | --- | ---
4Mx16 DRAM|TSOP(II)| U6 | 1 | Ali Express or E-Bay| K4E641612D or GM71VS65163
XC9572XL-10VQ64C|64-VQFP|U5|1|DigiKey|122-1266-ND or 122-1982-ND
AP2210N-3.3TRG1|SOT-23-3|U2|1|DigiKey|AP2210N-3.3TRG1DICT-ND
SN74LVC245A|SOIC|U3,U4|2|DigiKey|296-1232-1-ND
Ferrite Bead (600 Ohms@100MHz)|1206|FB1|1|DigiKey|MH3261-601YCT-ND
0.1uF Ceramic Capacitor|1206|C3-12|10|DigiKey|1276-2744-1-ND
4.7uF Ceramic Capacitor|1206|C1|1|DigiKey|1276-1055-1-ND
10uF Ceramic Capacitor|1206|C2|1|DigiKey|1276-1853-1-ND
6 Pin Male 2.54 Pitch Header (Optional)|--|J1|1|DigiKey|1849-PR20206VBNN-ND‎

# Revision History

V0.5 - Prototype Revision
V0.6 - Added missing trace between U3 pin 1 and U4 pin 1
V0.7 - Added ground planes
