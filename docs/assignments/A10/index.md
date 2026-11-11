# A10 – Lead Screw Translating System

## Objective

## CAD Model (Taye Mansour)
The CAD model was made using the dimensions calculated above and from the flange size. The holes in the crosshead need to be larger than the leadscrew and have clearance, because only the flange is supporting the weight. Since the outer diameter of the leadscrew is .5" we decided to use .6" for the hole diameter. The other parts needed for the assembly were downloaded from McMaster-Carr. Using the crosshead and leadscrew lengths, the lengths of the frame was determined to be 1.5ft across and 2ft vertically. When using those filters on a double slotted rail(as shown in figure #1 of the assignment) there were only two options, either 2"x1" or 3"x1.5". Unfortunately the download for the 3x1.5 frame was not working for some reason, so the only option was to use the 2x1 frame(McMaster-Carr part number 47065T107).

<img width="1522" height="687" alt="a10_crosshead" src="https://github.com/user-attachments/assets/994ea423-0ed5-465a-880c-9d5af40850fd" />
<img width="770" height="151" alt="a10_parametric" src="https://github.com/user-attachments/assets/7c0b4d44-dce1-4f64-82ce-b9aa74147eee" />
<img width="683" height="1122" alt="a10_assembly" src="https://github.com/user-attachments/assets/8ad148a2-525f-450c-a6a7-b5d1f24e6a3c" />

## FEA 2157 (Taye Mansour)
The fixed supports are connected where the flange would touch, they are fixed because in real life there would be bolts holding them together. The 2kN load was decided to be a square right in the middle because in figure #1 the gripper appears to connect to a square bracket.

<img width="1456" height="266" alt="a10_fea supports" src="https://github.com/user-attachments/assets/0f31768f-5322-4220-aa2c-fc2c55f0ba8d" />

The FEA was ran at the coarsest, medium, and finest mesh sizes, but convergence was not achieved so the images below show the finest mesh size.

<img width="30%" height="122" alt="a10_bigmesh" src="https://github.com/user-attachments/assets/d61177a9-2c5d-49b4-bb25-5669e34fcb72" />
<img width="30%" height="130" alt="a10_medmesh" src="https://github.com/user-attachments/assets/4e093a77-b2dd-4820-8b52-646a2d925996" />
<img width="30%" height="128" alt="a10_smallmesh" src="https://github.com/user-attachments/assets/17a989af-3c52-40a0-bd71-3ce8bf81a4c9" />

**Safety factor**
<img width="1408" height="542" alt="a10_SF1" src="https://github.com/user-attachments/assets/c631a626-196f-4ab8-867a-c222b61bcd77" />
**Stress**
<img width="1401" height="642" alt="a10_Stress1" src="https://github.com/user-attachments/assets/999e447b-5c0b-49c1-9d0b-a49e52752742" />
**Deflection**
<img width="1301" height="632" alt="a10_Defl1" src="https://github.com/user-attachments/assets/adceb56d-7e60-40f6-8268-739e23e1a512" />
**Convergence calculations (for both)**
<img width="785" height="220" alt="a10_convergence" src="https://github.com/user-attachments/assets/246cf772-e7c1-4be9-9cac-cbdab69a6237" />

**Optimization**
The changes made to optimize the design were to increase the thickness from 1.11" to 1.5" to increase strength and add cutouts on both sides to reduce weight. Again the FEA was ran at the coarsest, medium, and finest mesh sizes, but convergence was not achieved so the images below show the finest mesh size.

**Safety factor**
<img width="1530" height="642" alt="a10_SF2" src="https://github.com/user-attachments/assets/2eda3983-22b3-459b-8d8b-dc84e204426b" />
**Stress**
<img width="1600" height="700" alt="a10_Stress2" src="https://github.com/user-attachments/assets/175b3b01-7a25-4dd0-bef8-615bf09fd1ac" />
**Deflection**
<img width="1436" height="673" alt="a10_Defl2" src="https://github.com/user-attachments/assets/23ddb389-09f2-48da-9a95-8759d07d31ce" />
**Convergence**


## Drawing
<img width="1447" height="1120" alt="a10_Drawing" src="https://github.com/user-attachments/assets/431596a0-4b61-4123-9ea1-254262dac2a5" />




