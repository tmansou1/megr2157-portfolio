# A4 – [Topic]

## Objective

Design a motor mount using the (Brushed 24V DC Gear Motor 3.6Kg.cm/46RPM w/ 99.5:1 Planetary Gearbox) which attaches to a rigid wall. For both features use the two beam bending equations, one for max stress and the other for max deflection of .3mm at the free end. I used PLA as the material with a young’s modulus of 3GPa and used a safety factor of 3 which was given.

## Analyze

# Feature 1

I used 60MPa as the yield strength for PLA from a range of 30-60MPa. To solve for the moment created by force P, I used the dimensions of the motor and used the 12mm long flat part of the shaft as my length, because the rest of the motor will be inside/behind the mount. Rearranging the equations to solve for height(thickness), I got 9.86mm from the deflection equation and 5.19mm from the stress equation. Because we want the safer option when designing, I used the 9.86mm thickness in my design. Shown below are my calculations for both feature 1 and feature 2, because they use the same equations and many of the same variables.

<img width="4283" height="4268" alt="IMG_0760" src="https://github.com/user-attachments/assets/9d753bbc-5635-4abe-8241-1ba2d52a707f" />


# Feature 2

For feature 2 I needed the length L_2 which came from the thickness in feature 1, plus half the diameter of the lower bolt holes, and 7mm extra for the distance I wanted the holes set back from the edges. Using the same equations as feature 1, I calculated the height from the deflection equation to be 5.91mm and from the stress equation to be 5.19mm. Again, using the larger of the two for safety, I used 5.91mm in my design. The entire length of feature 2 wasn’t specified, I chose the same as feature 1 so each side will have the same square area.

# Sketch

Isometric view

<img width="1650" height="2200" alt="IMG_0754 (2)" src="https://github.com/user-attachments/assets/df3816e6-71c8-4073-9399-188093ad237d" />

FBD

<img width="1451" height="1490" alt="IMG_0754" src="https://github.com/user-attachments/assets/7a0d60d3-f4e1-4539-a1c5-74a82743157c" />

<img width="1451" height="1490" alt="IMG_0754 (1)" src="https://github.com/user-attachments/assets/bf308c30-208c-4533-9e57-ef03f850d07d" />

# CAD
I started my design with the flat plate of feature 1, then added circular cuts and holes to fit the motor into place, next I extruded feature 2 and added the holes for the bolts into the side, then finally I added a 1mm fillet on the interior edge to minimize deflection. Images of each step are shown below including my equation table for global variables used in dimensions.


<img width="951" height="702" alt="cad1" src="https://github.com/user-attachments/assets/6213eb3e-5314-4e83-8a5b-fcd3fbfabcc7" />
<img width="872" height="656" alt="cad2" src="https://github.com/user-attachments/assets/52199215-89a0-43a1-9015-f606cd3d08bc" />
<img width="948" height="1086" alt="cad3" src="https://github.com/user-attachments/assets/31c62c8c-2f7e-4862-92df-8beba0714da5" />
<img width="958" height="1080" alt="cad4" src="https://github.com/user-attachments/assets/ddd47236-82dd-47e3-be20-bdd8d834c24b" />
<img width="1002" height="1097" alt="cad5" src="https://github.com/user-attachments/assets/e40be7ad-27b3-4032-a62a-ceb03b5f1f69" />
<img width="576" height="277" alt="cadtable" src="https://github.com/user-attachments/assets/dac965bd-92d3-4e34-b073-a6c03666c796" />



## Decide


## Communicate

