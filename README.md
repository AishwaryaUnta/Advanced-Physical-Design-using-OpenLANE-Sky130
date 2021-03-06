# Advanced-Physical-Design-using-OpenLANE-Sky130
<p align="center">
    <img src="https://www.vlsisystemdesign.com/wp-content/uploads/2020/10/Advanced-Physical-Design-using-OpenLANE_Sky130_1-1024x576.png">
</p>

# OpenLANE Overview
OpenLANE is an complete automated RTL to GDSII flow based on several blocks including OpenROAD, Yosys, Magic, Netgen, Fault, OpenPhySyn, SPEF-Extractor and custom methodology scripts for design exploration and optimization. The flow performs full ASIC implementation steps from RTL all the way down to GDSII.

<p align="center">
    DAY 1
</p>
<p align ="left">
RTL IP's--------|
</p>
<p align ="left">
EDA Tools ------| - ASIC
</p>
<p align ="left">
PDK Data -------|
</p>

 <p align="center">
    <img src="https://github.com/AishwaryaUnta/Advanced-Physical-Design-using-OpenLANE-Sky130/blob/main/images/Day1/openlane_flowchart1.png">
</p>

ASIC Flow Objective : RTL to GDSII

 <p align="center">
    <img src="https://github.com/AishwaryaUnta/Advanced-Physical-Design-using-OpenLANE-Sky130/blob/main/images/Day1/rtl2gds1.png">
</p>

<p align="left">
Inputs :RTL files and PDK(Process Design Kit)
</p>
<p align="left">
Synthesis-> Floorplanning -> Placement -> Clock Tree Synthesis -> Routing -> Signoff
</p>
<p align="left">
 Output : GDSII
</p>

OpenLANE Directory Structure in detail:
 OpenLANE is a flow which comprises of many opensource tools like Yosys,OpenSTA etc.
 <p align="center">
    <img src="https://github.com/AishwaryaUnta/Advanced-Physical-Design-using-OpenLANE-Sky130/blob/main/images/Day1/Capture1.JPG">
</p>
<p align="center">
    <img src="https://github.com/AishwaryaUnta/Advanced-Physical-Design-using-OpenLANE-Sky130/blob/main/images/Day1/Capture2.JPG">
</p>
<p align="center">
    <img src="https://github.com/AishwaryaUnta/Advanced-Physical-Design-using-OpenLANE-Sky130/blob/main/images/Day1/Capture3.JPG">
</p>
<p align="center">
    <img src="https://github.com/AishwaryaUnta/Advanced-Physical-Design-using-OpenLANE-Sky130/blob/main/images/Day1/Capture4.JPG">
</p>
<p align="center">
    <img src="https://github.com/AishwaryaUnta/Advanced-Physical-Design-using-OpenLANE-Sky130/blob/main/images/Day1/Capture5.JPG">
</p>
<p align="center">
    <img src="https://github.com/AishwaryaUnta/Advanced-Physical-Design-using-OpenLANE-Sky130/blob/main/images/Day1/Capture6.JPG">
</p>
<p align="center">
    <img src="https://github.com/AishwaryaUnta/Advanced-Physical-Design-using-OpenLANE-Sky130/blob/main/images/Day1/Capture7.JPG">
</p>
<p align="center">
    <img src="https://github.com/AishwaryaUnta/Advanced-Physical-Design-using-OpenLANE-Sky130/blob/main/images/Day1/Capture8.JPG">
</p>
<p align="center">
    <img src="https://github.com/AishwaryaUnta/Advanced-Physical-Design-using-OpenLANE-Sky130/blob/main/images/Day1/Capture9.JPG">
</p>
<p align="center">
    <img src="https://github.com/AishwaryaUnta/Advanced-Physical-Design-using-OpenLANE-Sky130/blob/main/images/Day1/Capture10.JPG">
</p>
<p align="center">
    <img src="https://github.com/AishwaryaUnta/Advanced-Physical-Design-using-OpenLANE-Sky130/blob/main/images/Day1/Capture11.JPG">
</p>
<p align="center">
    <img src="https://github.com/AishwaryaUnta/Advanced-Physical-Design-using-OpenLANE-Sky130/blob/main/images/Day1/Capture12.JPG">
</p>
<p align="center">
    <img src="https://github.com/AishwaryaUnta/Advanced-Physical-Design-using-OpenLANE-Sky130/blob/main/images/Day1/Capture13.JPG">
</p>
<p align="center">
    <img src="https://github.com/AishwaryaUnta/Advanced-Physical-Design-using-OpenLANE-Sky130/blob/main/images/Day1/Capture14.JPG">
</p>
<p align="center">
    <img src="https://github.com/AishwaryaUnta/Advanced-Physical-Design-using-OpenLANE-Sky130/blob/main/images/Day1/Capture15.JPG">
</p>

# Invoking OpenLANE
<p align="center">
    <img src="https://github.com/AishwaryaUnta/Advanced-Physical-Design-using-OpenLANE-Sky130/blob/main/images/Day1/Capture16.JPG">
</p>
<p align="center">
    <img src="https://github.com/AishwaryaUnta/Advanced-Physical-Design-using-OpenLANE-Sky130/blob/main/images/Day1/Capture17.JPG">
</p>
<p align="center">
    <img src="https://github.com/AishwaryaUnta/Advanced-Physical-Design-using-OpenLANE-Sky130/blob/main/images/Day1/Capture20.JPG">
</p>
<p align="center">
    <img src="https://github.com/AishwaryaUnta/Advanced-Physical-Design-using-OpenLANE-Sky130/blob/main/images/Day1/Capture26.JPG">
</p>
<p align="center">
    <img src="https://github.com/AishwaryaUnta/Advanced-Physical-Design-using-OpenLANE-Sky130/blob/main/images/Day1/Capture27.JPG">
</p>
<p align="center">
    <img src="https://github.com/AishwaryaUnta/Advanced-Physical-Design-using-OpenLANE-Sky130/blob/main/images/Day1/Capture32.JPG">
</p>
<p align="center">
    <img src="https://github.com/AishwaryaUnta/Advanced-Physical-Design-using-OpenLANE-Sky130/blob/main/images/Day1/Capture33.JPG">
</p>
<p align="center">
    <img src="https://github.com/AishwaryaUnta/Advanced-Physical-Design-using-OpenLANE-Sky130/blob/main/images/Day1/Capture36.JPG">
</p>
 
 
<p align="center">
 Day 2
</p>
<p align="center">
    <img src="https://github.com/AishwaryaUnta/Advanced-Physical-Design-using-OpenLANE-Sky130/blob/main/images/Day2/Capture1.JPG">
</p>
<p align="center">
    <img src="https://github.com/AishwaryaUnta/Advanced-Physical-Design-using-OpenLANE-Sky130/blob/main/images/Day2/Capture2.JPG">
</p>
<p align="center">
    <img src="https://github.com/AishwaryaUnta/Advanced-Physical-Design-using-OpenLANE-Sky130/blob/main/images/Day2/Capture3.JPG">
</p>
<p align="center">
    <img src="https://github.com/AishwaryaUnta/Advanced-Physical-Design-using-OpenLANE-Sky130/blob/main/images/Day2/Capture4.JPG">
</p>
<p align="center">
    <img src="https://github.com/AishwaryaUnta/Advanced-Physical-Design-using-OpenLANE-Sky130/blob/main/images/Day2/Capture%205.JPG">
</p>

<p align="center">
    <img src="https://github.com/AishwaryaUnta/Advanced-Physical-Design-using-OpenLANE-Sky130/blob/main/images/Day2/Capture6.JPG">
</p>
<p align="center">
    <img src="https://github.com/AishwaryaUnta/Advanced-Physical-Design-using-OpenLANE-Sky130/blob/main/images/Day2/Capture7.JPG">
</p>
<p align="center">
    <img src="https://github.com/AishwaryaUnta/Advanced-Physical-Design-using-OpenLANE-Sky130/blob/main/images/Day2/Capture8.JPG">
</p>
<p align="center">
    <img src="https://github.com/AishwaryaUnta/Advanced-Physical-Design-using-OpenLANE-Sky130/blob/main/images/Day2/Capture9.JPG">
</p>
<p align="center">
    <img src="https://github.com/AishwaryaUnta/Advanced-Physical-Design-using-OpenLANE-Sky130/blob/main/images/Day2/Capture10.JPG">
</p>
<p align="center">
    <img src="https://github.com/AishwaryaUnta/Advanced-Physical-Design-using-OpenLANE-Sky130/blob/main/images/Day2/Capture11.JPG">
</p>
<p align="center">
    <img src="https://github.com/AishwaryaUnta/Advanced-Physical-Design-using-OpenLANE-Sky130/blob/main/images/Day2/Capture12.JPG">
</p>



<p align="center">    
 Day 3
</p>  

<p align="left">
16 Mask CMOS Process:

Substrate Selection is the base layer on which other regions will be formed.</p>
SiO2 and Si3N2 deposited. Photoresist is spinned. Pockets created using lithography process using masks.</p>
Nwell & Pwell formation took place and Gate terminal was created</p>
LDD was carried out to avoid hot electron effect and short channel effect.</p>
Source and Drain formation took place.</p>
Contacts & local interconnect were created.</p>
Higher Level metal layer formation took place.</p>
Here 16 masks were used at various stages throughout the process.</p>
<p align="center">
    <img src="https://github.com/AishwaryaUnta/Advanced-Physical-Design-using-OpenLANE-Sky130/blob/main/images/Day%203/Capture31.jpg">
</p>
<p align="center">
    <img src="https://github.com/AishwaryaUnta/Advanced-Physical-Design-using-OpenLANE-Sky130/blob/main/images/Day%203/Capture33.jpg">
</p>
<p align="center">
    <img src="https://github.com/AishwaryaUnta/Advanced-Physical-Design-using-OpenLANE-Sky130/blob/main/images/Day%203/Capture32.jpg">
</p>

<p align="center">    
 Day 4
</p> 
<p align="center">
    <img src="https://github.com/AishwaryaUnta/Advanced-Physical-Design-using-OpenLANE-Sky130/blob/main/images/Day%204/Capture42.JPG">
</p>
<p align="center">    
 Day 5
</p>  
<p align="center">
    <img src="https://github.com/AishwaryaUnta/Advanced-Physical-Design-using-OpenLANE-Sky130/blob/main/images/Day%205/Capture1.JPG">
</p>

# Acknowledgements
<p align="left">
Kunal Ghosh.</p>
Nickson Jose.</p>
Praharsha Mahurkar.</p>
Akurathi Radhika.</p>
