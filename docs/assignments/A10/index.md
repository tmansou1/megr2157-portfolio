# A10 – Lead Screw Translating System


## Designing the Crosshead (Logan Dreifuss)
I discussed with my teammates regarding what beam analysis model to use: "both ends overhanging supports", "supported at both ends", or "fixed at both ends". We decided on "fixed at both ends" model, because that prevents the crosshead from twisting at its ends.

<img width="1892" height="2220" alt="Notes page 1" src="https://github.com/user-attachments/assets/2e7480c2-1f30-40df-81a8-9afa7ddd5450" />

The diameter of the flange that the team decided on was 1.25 inches, so I used that for the minimum base dimension (converting to mm, which results in a base length of 31.75 mm). With a combination of research and the knowing the height of the lead screws we were using, we decided that the length of the crosshead (between the centerlines of the lead screws) would be 1 foot (which, converted to metric, is 304.8 millimeters).

The team decided that the material for the crosshead would be ASTM A36 steel, which has an elastic modulus of 2x10^11 N/m^2, and a yield strength equal to 2.5x10^8 N/m^2. As such, the stress/strain analysis resulted in a height of 1.054x10^-3 mm, and the deflection analysis resulted in a height of 28.145 mm, which is the height we decided to use for the crosshead.

<img width="2362" height="1272" alt="Notes page 2" src="https://github.com/user-attachments/assets/667e8a62-0045-496c-a835-435db46d5c6c" />

### Drawings:

<img width="3065" height="1342" alt="CamScanner 11-09-2026 14 49_1" src="https://github.com/user-attachments/assets/03988416-a250-4129-87b9-21009488312b" />

<img width="3007" height="1345" alt="CamScanner 11-09-2026 14 49_2" src="https://github.com/user-attachments/assets/44a0de25-6eec-4aea-b1d5-55067b24e85b" />

## Tabulating Costs (Logan Dreifuss)

| Item Number | Quantity | Name | Cost/Item | Cost | Purchase Link |
| --- | --- | --- | --- | --- | --- |
| #1 | 2 | Lead Screw | $6.95 | $13.90 | [Lead Screw Purchase Link](https://www.mcmaster.com/98935A911/) |
| #2 | 2 | Flange Nut | $125.72 | $251.44 | [Flange Nut Purchase Link](https://www.mcmaster.com/95120A111/) |
| --- | --- | --- | Total Cost: | $265.34 | --- |

## CAD Model (Taye Mansour)
Using A36 steel for material. The CAD model was made using the dimensions calculated above and from the flange size. The holes in the crosshead need to be larger than the leadscrew and have clearance, because only the flange is supporting the weight. Since the outer diameter of the leadscrew is .5" we decided to use .6" for the hole diameter. The other parts needed for the assembly were downloaded from McMaster-Carr. Using the crosshead and leadscrew lengths, the lengths of the frame were determined to be 1.5ft across and 2ft vertically. When using those filters on a double slotted rail(as shown in figure #1 of the assignment) there were only two options, either 2"x1" or 3"x1.5". Unfortunately the download for the 3x1.5 frame was not working for some reason, so the only option was to use the 2x1 frame(McMaster-Carr part number 47065T107).

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
<img width="3544" height="3399" alt="IMG_0995" src="https://github.com/user-attachments/assets/682b3d43-a1da-42fd-adaf-12cafb9c1a37" />


**Optimization**
The changes made to optimize the design were to increase the thickness from 1.11" to 1.5" to increase strength and add cutouts on both sides to reduce weight. Again the FEA was ran at the coarsest, medium, and finest mesh sizes, but convergence was not achieved so the images below show the finest mesh size.

**Safety factor**
<img width="1530" height="642" alt="a10_SF2" src="https://github.com/user-attachments/assets/2eda3983-22b3-459b-8d8b-dc84e204426b" />
**Stress**
<img width="1600" height="700" alt="a10_Stress2" src="https://github.com/user-attachments/assets/175b3b01-7a25-4dd0-bef8-615bf09fd1ac" />
**Deflection**
<img width="1436" height="673" alt="a10_Defl2" src="https://github.com/user-attachments/assets/23ddb389-09f2-48da-9a95-8759d07d31ce" />
**Convergence**
<img width="3430" height="2854" alt="IMG_0996" src="https://github.com/user-attachments/assets/11d4b739-d8c7-472f-a49f-63ba10f4ad3e" />

**Notes**
The locations of each max and min for the second design are nearly identical to the original design. For max stress and min SF they're on the bottom side next to a hole, and for max deflection it's in the center of the beam. The min safety factor for both the original and optimization was above the required of 4. The original weight was 5.04lbs and the optimized weight was 5.47lbs, but it was stronger.

## Drawing
<img width="1447" height="1120" alt="a10_Drawing" src="https://github.com/user-attachments/assets/431596a0-4b61-4123-9ea1-254262dac2a5" />




