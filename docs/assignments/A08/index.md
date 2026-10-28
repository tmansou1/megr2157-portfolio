# A8 – Gearbox

## Objective
Design a gearbox that can be assembled and disassembled.

Analyze and size input and output shafts for strength.

Design journal bearings to support shafts.

Create a gearbox housing with proper clearance and fastening.

Use parametric CAD modeling to generate a final design.

Document calculations, sketches, and lessons learned.

## Shafts
What’s given: 24:9, shaft material 1045 steel with Sy of 77000psi, output torque = 1.25 in-lb, 1100 rpm output, input shaft diameter = .125”, output shaft diameter = .25”, and shaft length = 1”. 

Using the equations from the machinery’s handbook and slides I determined if the diameter of each shaft is large enough to withstand the force. Shown below are my handwritten equations solved algebraically then numerically.

<img width="3792" height="3517" alt="IMG_0952" src="https://github.com/user-attachments/assets/f31853eb-4b5a-47cb-907c-64c261189719" />

I was able to confirm that both of the given shaft diameters are sufficient.

## Journal Bearings
For each journal bearing I used a length of .25” because on each 1” shaft there needs to be enough room for 2 bearings and the gear. Using this dimension I solved for P and V. Shown below are my handwritten equations solved algebraically then numerically.

<img width="3720" height="3941" alt="IMG_0953" src="https://github.com/user-attachments/assets/b7b0bb68-e957-4d12-b311-0d92db892ee3" />

Given the P, V, and PV, I selected 841 bearing bronze specifically, because it has the appropriate PV rating and is a common metal for bearings listed on McMaster-Carr. Each calculated thickness was much below the smallest sized bearings listed, so I used the smallest thickness of 1/16” resulting in outer diameters of 3/16” and 5/16”. The two bearings I chose are 6391K753 and 6391K126 on McMaster-Carr.

## Housing Fittings Sketch
The two sides of the housing could be attached by nuts and bolts on each corner, as shown below.

<img width="2383" height="1762" alt="IMG_0954" src="https://github.com/user-attachments/assets/ffdd8e93-1472-4f9b-b069-cb935514c42e" />

## CAD Models
This is one half of the housing, the rest is a mirrored copy. I have room for the bearings on either side and added an extra hole so the shafts wouldn't rub against the housing.

<img width="1097" height="878" alt="a8Housing" src="https://github.com/user-attachments/assets/2df5bad7-bc80-4106-aa84-a981350d04bd" />

Here is my full gearbox assembly.

<img width="981" height="917" alt="a8gearboxopen" src="https://github.com/user-attachments/assets/dff0300f-b4e3-4099-8f97-2deec11aad4e" />
<img width="1057" height="977" alt="a8GearboxClosed" src="https://github.com/user-attachments/assets/2bcd813f-5225-49db-a179-8a8edad8c876" />


Other CAD models like the shafts and premade gears and bearings are available for download in the final assembly at the bottom of this page.


## Drawings (MEGR 2157)
Here are the drawings for each shaft, the chosen journal bearings, the housing (and mirrored), and the full gearbox assembly.

<img width="1437" height="1108" alt="z1" src="https://github.com/user-attachments/assets/3ecf3562-267c-4eab-9fa9-a35d89587caa" />
<img width="1446" height="1113" alt="z2" src="https://github.com/user-attachments/assets/145ff79d-5ae9-47c6-aeb1-4fa2ce37429b" />
<img width="1441" height="1112" alt="z3" src="https://github.com/user-attachments/assets/93819b9e-b3d7-4213-8140-526ec4385841" />
<img width="1440" height="1110" alt="z4" src="https://github.com/user-attachments/assets/2da2b860-61af-4963-8a57-9b3483d2d621" />
<img width="1437" height="1112" alt="z5" src="https://github.com/user-attachments/assets/1f993d0c-7a99-4074-b591-b79a960fcb44" />
<img width="1438" height="1112" alt="z6" src="https://github.com/user-attachments/assets/0d5f5eb5-fe52-4d5f-968c-98960964e35d" />
<img width="1442" height="1116" alt="z7" src="https://github.com/user-attachments/assets/518fa9f2-c65b-48a8-b252-392070d3d8f0" />


## Lessons learned
I learned how to calculate bearing sizes to match my designs.
I learned how to properly constrain parts in an assembly.

-This assignment took 8 hours total.



