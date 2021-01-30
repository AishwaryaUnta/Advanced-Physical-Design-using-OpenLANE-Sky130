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


ASIC Flow Objective : RTL to GDSII

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
 Day 2
</p> 




<p align="center">    
 Day 3
</p>  

<p align="left">
16 Mask CMOS Process Steps

Substrate Selection : Selection of base layer on which other regions will be formed.</p>
Create an active region for transistors : SiO2 and Si3N2 deposited. Pockets created using photoresist and lithography.</p>
Nwell & Pwell formation : Pwell uses boron and nwell uses phosphorus. Drive in diffusion by placing it in a high temperature furnace.</p>
Creating Gate terminal : For desired threshold value NA (doping Concentration) and Cox to be set.</p>
Lightly Doped Drain (LDD) formation : LDD done to avoid hot electron effect and short channel effect.</p>
Source and Drain formation : Forming the source and drain.</p>
Contacts & local interconnect Creation : SiO2 removed using HF etch. Titanium deposited using sputtering.</p>
Higher Level metal layer formation : Upper layers of metals deposited.</p>
</p>

<p align="center">    
 Day 4
</p>    
<p align="center">    
 Day 5
</p>    
