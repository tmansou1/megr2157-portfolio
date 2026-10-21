# A7 – FEA on Breacket

## Objectives

Use Finite Element Analysis (FEA) to improve the bracket design from previous assignments.

Ensure high stiffness, strength, and lightweight optimization through iterative design.

Conduct multiple FEA simulations, refining geometry based on results.

Perform static stress analysis, including constraints, loading, and meshing selection.

Interpret data by identifying max stress, displacement, and safety factors.

Optimize the design by modifying geometry to enhance performance.

Document the entire process with images, calculations, and insights.

Reflect on key engineering lessons learned and time spent.

## Design #1

Using my original bracket design I ran an FEA for SF, stress, and deflection. The first mesh size I used was automatically in the middle of mesh sizes. My second mesh was in between the last and the smallest sized mesh. My third and last mesh is the smallest possible.

For each design I added fixed supports on each inside face that would touch the T beam, and added a bearing load downwards on the pin.

Shown below are images of the mesh and each FEA result. Also shown are my handwritten values and calculations for error estimation.

1a.

<img width="277" height="127" alt="123MeshBig" src="https://github.com/user-attachments/assets/1b438b0c-5fce-47a0-acab-2de20576c92d" />

<img width="550" height="826" alt="1aMesh" src="https://github.com/user-attachments/assets/c0120e75-04e9-44f2-9bb2-baaee7d74799" />
<img width="808" height="802" alt="1aSF" src="https://github.com/user-attachments/assets/4d636587-0e5a-4f30-bcf4-891a45bf5c50" />
<img width="923" height="893" alt="1aStress" src="https://github.com/user-attachments/assets/13c80004-01c5-4086-abf8-c673004bd624" />
<img width="796" height="910" alt="1aDef" src="https://github.com/user-attachments/assets/8083732a-1143-465e-baa0-b0fb42754bf0" />

1b.

<img width="276" height="137" alt="123MeshMed" src="https://github.com/user-attachments/assets/e2c5cc9e-a08d-4cc9-9405-e23451678f46" />

<img width="546" height="827" alt="1bMesh" src="https://github.com/user-attachments/assets/0331fd4d-776a-4de4-a9dd-e0e16af6524c" />
<img width="812" height="816" alt="1bSF" src="https://github.com/user-attachments/assets/dd765776-9f2a-43e1-9d78-4aa6eee7b237" />
<img width="976" height="923" alt="1bStress" src="https://github.com/user-attachments/assets/f7559108-8891-490f-b860-93eae748c7b6" />
<img width="837" height="877" alt="1bDef" src="https://github.com/user-attachments/assets/7e42ea43-a1bf-4512-895f-bbae665f772b" />

1c.

<img width="276" height="130" alt="123MeshSmall" src="https://github.com/user-attachments/assets/64ff508d-0ae2-48f6-95f9-8e750b1987ff" />

<img width="929" height="1021" alt="1cMesh" src="https://github.com/user-attachments/assets/caccac8c-0cd5-4b95-8c94-5308a4120a20" />
<img width="827" height="957" alt="1cSF" src="https://github.com/user-attachments/assets/066a343a-0d6f-42f7-a36a-40ae52317e51" />
<img width="953" height="997" alt="1cStress" src="https://github.com/user-attachments/assets/65d2341e-c1c7-4244-a5b3-fff52e8209c4" />
<img width="868" height="1006" alt="1cDef" src="https://github.com/user-attachments/assets/6e639ae1-0e25-462c-b781-c6df126d6cd6" />

My error estimation was above 7% so it did'nt reach convergence, but it was 3 tests.

## Design #2

For my second design I shrank the thickness of the upper and lower horizontal beams to reduce weight, and increased the thickness of the beam holding the pin to reduce max stress at that location.

Shown below are images of the mesh and each FEA result. Also shown are my handwritten values and calculations for error estimation.

2a.

<img width="277" height="127" alt="123MeshBig" src="https://github.com/user-attachments/assets/39f8b3c9-4bcd-4400-9746-6eaabf23bb7e" />

<img width="740" height="970" alt="2aMesh" src="https://github.com/user-attachments/assets/a020df8b-f3ef-48e8-9c52-39ae41d1656f" />
<img width="885" height="912" alt="2aSF" src="https://github.com/user-attachments/assets/aa684795-807b-438e-88c1-ac46e504e711" />
<img width="1012" height="956" alt="2aStress" src="https://github.com/user-attachments/assets/f2a4fb8e-a72c-4e57-aca2-48287fcb074e" />
<img width="916" height="927" alt="2aDef" src="https://github.com/user-attachments/assets/0c481a35-8a1a-4c30-9705-9257159e1105" />

2b.

<img width="276" height="137" alt="123MeshMed" src="https://github.com/user-attachments/assets/a4910ad0-c547-4b1f-8f0b-af2a19d0f640" />

<img width="700" height="913" alt="2bMesh" src="https://github.com/user-attachments/assets/b7cbc1c8-26b2-4666-9ed2-d501d1b8f297" />
<img width="893" height="917" alt="2bSF" src="https://github.com/user-attachments/assets/ffc7b96f-d66d-4255-9329-5e56b9981746" />
<img width="1007" height="943" alt="2bStress" src="https://github.com/user-attachments/assets/ed4c271a-a97d-49e7-8df3-165a81f0a63e" />
<img width="917" height="946" alt="2bDef" src="https://github.com/user-attachments/assets/a1495ba0-b67c-4753-9ed5-2f93d00f7be3" />

2c.

<img width="276" height="130" alt="123MeshSmall" src="https://github.com/user-attachments/assets/c739778d-7071-4280-8db5-4a2cdf92a973" />

<img width="706" height="926" alt="2cMesh" src="https://github.com/user-attachments/assets/71e122f0-58a5-4840-babf-b88d1be1cabf" />
<img width="883" height="918" alt="2cSF" src="https://github.com/user-attachments/assets/9b5427f8-dde0-4930-be8f-e5fd89bb1e5b" />
<img width="981" height="931" alt="2cStress" src="https://github.com/user-attachments/assets/a1b56850-0abb-44ea-b2b3-a2c082500c03" />
<img width="906" height="935" alt="2cDef" src="https://github.com/user-attachments/assets/527811f2-6813-469d-98ea-4df2ec8f553d" />

My error estimation was above 7% so it did'nt reach convergence, but it was 3 tests.

## Design #3

For the third design I added holes in the top beams and shrank the bottom beam even more to reduce weight, and added fillets on the edges near the pin and each corner to reduce stress.

Shown below are images of the mesh and each FEA result. Also shown are my handwritten values and calculations for error estimation.

3a.

<img width="277" height="127" alt="123MeshBig" src="https://github.com/user-attachments/assets/6ce6a15a-b9a1-4e81-8f2a-36ec8df6620c" />

<img width="806" height="937" alt="3aMesh" src="https://github.com/user-attachments/assets/6fdf8d82-30c3-40ce-bd2f-74443cb70adb" />
<img width="905" height="900" alt="3aSF" src="https://github.com/user-attachments/assets/2cc97b71-e8f1-4f34-b607-5aca095d3af5" />
<img width="982" height="917" alt="3aStress" src="https://github.com/user-attachments/assets/d24301ff-d3e3-4f8e-a893-bb8d466e39bf" />
<img width="896" height="921" alt="3aDef" src="https://github.com/user-attachments/assets/02ae14c0-e7de-4293-9a73-c9d4207bb677" />

3b.

<img width="276" height="137" alt="123MeshMed" src="https://github.com/user-attachments/assets/89cd8437-6c35-4cd8-83d5-f54d560bf7fb" />

<img width="777" height="912" alt="3bMesh" src="https://github.com/user-attachments/assets/3394ad30-0830-45d8-a9da-9751740963f4" />
<img width="897" height="903" alt="3bSF" src="https://github.com/user-attachments/assets/338c2d5b-f2bb-4c59-9b49-6fdf25e40c06" />
<img width="972" height="938" alt="3bStress" src="https://github.com/user-attachments/assets/08bf3c2e-0e38-46c2-aabb-9ad1702115c4" />
<img width="893" height="927" alt="3bDef" src="https://github.com/user-attachments/assets/b3f7ec0f-aa9f-419c-8771-36d2fd9ea3ef" />


My error estimation was below 7% so it did reach convergence, after 2 tests.



## Link FEA (MEGR 2157)

Completing the same process for the link, I started with my original design for the first run. 


<a href="https://github.com/tmansou1/megr2157-portfolio/raw/refs/heads/main/A4_MotorMount.SLDPRT" download>Download CAD Bracket Design #1</a>

<a href="https://github.com/tmansou1/megr2157-portfolio/raw/refs/heads/main/A4_MotorMount.SLDPRT" download>Download CAD Bracket Design #2</a>

<a href="https://github.com/tmansou1/megr2157-portfolio/raw/refs/heads/main/A4_MotorMount.SLDPRT" download>Download CAD Bracket Design #3</a>

<a href="https://github.com/tmansou1/megr2157-portfolio/raw/refs/heads/main/A4_MotorMount.SLDPRT" download>Download CAD Link Design #1</a>

<a href="https://github.com/tmansou1/megr2157-portfolio/raw/refs/heads/main/A4_MotorMount.SLDPRT" download>Download CAD Link Design #2</a>

<a href="https://github.com/tmansou1/megr2157-portfolio/raw/refs/heads/main/A4_MotorMount.SLDPRT" download>Download CAD Link Design #2</a>
