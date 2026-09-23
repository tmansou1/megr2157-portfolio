# A5 – Bracket Design

## Objective


## Analyze
In both my stress and stiffness analysis I assumed a few things;aluminum 6061 T6 has a yield stress of 40ksi, a Young's modulus of 10^6, chose a force F of 500lbs, and the thickness of the whole mount to be 1”, which comes from the thickness of the strap plus .25” extra. The dimensions of the T beam and SF of 4 are given.

## Feature A

For feature A I'm treating it as a cantilever beam with a distributed load of 2F. Shown below are my FBD and both the stress and stiffness calculations. The larger of the two diameters came from the stiffness analysis which was 0.845”.

<img width="50%" height="1147" alt="IMG_0791" src="https://github.com/user-attachments/assets/dd924524-1d43-44e0-aa76-64e85704827a" />
<img width="4087" height="2611" alt="IMG_0796" src="https://github.com/user-attachments/assets/e0116a84-d4b1-44c7-b3ee-d676cd4466d4" />



## Feature B

For feature B I'm treating it as an axial load with 2F force downwards. Shown below are my FBD and both the stress and stiffness calculations. The larger of the two h came from the stiffness analysis which was 0.159”.

<img width="50%" height="1179" alt="IMG_0791 (1)" src="https://github.com/user-attachments/assets/4e74fc33-728e-4d0d-aa53-3b7178e18c82" />

<img width="3849" height="1846" alt="IMG_0796 (1)" src="https://github.com/user-attachments/assets/7e599ed2-0daa-4d60-9f23-a995801a6e5d" />

## Feature C

For feature C I'm treating it as a simply supported beam with the same 2F force from feature B in the center. Shown below are my FBD and both the stress and stiffness calculations. The larger of the two h came from the stiffness analysis which was 0.9197”.

<img width="50%" height="1030" alt="IMG_0791 (2)" src="https://github.com/user-attachments/assets/888e20b4-13ea-4e6d-bae6-37bab5292c2e" />
<img width="3648" height="1813" alt="IMG_0797" src="https://github.com/user-attachments/assets/d6e401e8-3907-472d-aec6-abe78c61bcda" />


## Feature D

For feature D I'm treating it as an axial load with F downwards. Shown below are my FBD and both the stress and stiffness calculations. The larger of the two h came from the stiffness analysis which was 0.1499”.

<img width="50%" height="1036" alt="IMG_0791 (3)" src="https://github.com/user-attachments/assets/24b2750e-e5a3-4a79-a925-2f13357d297f" />
<img width="3272" height="1579" alt="IMG_0797 (1)" src="https://github.com/user-attachments/assets/38094469-5a92-49ea-bfd3-ca9561f92d8e" />


## Feature E

For feature E i’m treating it as a cantilever beam with a distributed load of F. Shown below are my FBD and both the stress and stiffness calculations. The larger of the two h came from the stress analysis which was 0.387”.

<img width="50%" height="1256" alt="IMG_0791 (4)" src="https://github.com/user-attachments/assets/900c3feb-198a-4edb-a822-1da21bf5728f" />
<img width="3513" height="1606" alt="IMG_0797 (2)" src="https://github.com/user-attachments/assets/a0e96b19-8073-49ac-8a48-1cceddaca213" />


## Multiview sketches

Shown below are the front and right views of the bracket with the dimensions calculated from the stress and stiffness/deflection analysis respectively. The top view is unnecessary.

<img width="4277" height="2661" alt="IMG_0798" src="https://github.com/user-attachments/assets/55d90350-df8e-44e4-b939-0793b174bc87" />
<img width="4133" height="2769" alt="IMG_0798 (1)" src="https://github.com/user-attachments/assets/675f5af4-d6f4-4be4-9b98-66a0aa44bcb7" />



## Lessons learned

For feature C, the stiffness governed the final dimension because stress required 0.387”, and stiffness required 0.9197”. Feature C had the greatest difference in results. One thing I noticed was that the diameter of feature A had to be the same as the width of feature B. If I realised I had messed up earlier and had to fix it, then I would get a different answer for feature B and redo that one too. One assumption I made was to neglect shear failure, if I didn’t, then the corner between features D and E or C and D could possibly break.

## Fits - MEGR 2157

For this part analysis the stress at the smallest area would be right next to the holes. I’m using half the force and the area of one side of the hole. I ended up getting a cross sectional area of 0.1in^2 which could have a width of .5” and thickness of .2”. Shown below are my calculations and the fits for each hole, found in the Machinery’s Handbook.

<img width="3024" height="4032" alt="IMG_0800" src="https://github.com/user-attachments/assets/6bbe747a-c360-4981-a247-0e051befcff5" />

**Sources**

https://www.modulusmetal.com/aluminum-6061-t6-mechanical-properties/ 

Machinery’s Handbook, pg.655, 661
