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
<img width="50%" height="826" alt="1aMesh" src="https://github.com/user-attachments/assets/c0120e75-04e9-44f2-9bb2-baaee7d74799" />
<img width="50%" height="802" alt="1aSF" src="https://github.com/user-attachments/assets/4d636587-0e5a-4f30-bcf4-891a45bf5c50" />
<img width="50%" height="893" alt="1aStress" src="https://github.com/user-attachments/assets/13c80004-01c5-4086-abf8-c673004bd624" />
<img width="50%" height="910" alt="1aDef" src="https://github.com/user-attachments/assets/8083732a-1143-465e-baa0-b0fb42754bf0" />

1b.

<img width="276" height="137" alt="123MeshMed" src="https://github.com/user-attachments/assets/e2c5cc9e-a08d-4cc9-9405-e23451678f46" />
<img width="50%" height="827" alt="1bMesh" src="https://github.com/user-attachments/assets/0331fd4d-776a-4de4-a9dd-e0e16af6524c" />
<img width="50%" height="816" alt="1bSF" src="https://github.com/user-attachments/assets/dd765776-9f2a-43e1-9d78-4aa6eee7b237" />
<img width="50%" height="923" alt="1bStress" src="https://github.com/user-attachments/assets/f7559108-8891-490f-b860-93eae748c7b6" />
<img width="50%" height="877" alt="1bDef" src="https://github.com/user-attachments/assets/7e42ea43-a1bf-4512-895f-bbae665f772b" />

1c.

<img width="276" height="130" alt="123MeshSmall" src="https://github.com/user-attachments/assets/64ff508d-0ae2-48f6-95f9-8e750b1987ff" />
<img width="50%" height="1021" alt="1cMesh" src="https://github.com/user-attachments/assets/caccac8c-0cd5-4b95-8c94-5308a4120a20" />
<img width="50%" height="957" alt="1cSF" src="https://github.com/user-attachments/assets/066a343a-0d6f-42f7-a36a-40ae52317e51" />
<img width="50%" height="997" alt="1cStress" src="https://github.com/user-attachments/assets/65d2341e-c1c7-4244-a5b3-fff52e8209c4" />
<img width="50%" height="1006" alt="1cDef" src="https://github.com/user-attachments/assets/6e639ae1-0e25-462c-b781-c6df126d6cd6" />

My error estimation was above 7% so it did'nt reach convergence, but it was 3 tests.

## Design #2

For my second design I shrank the thickness of the upper and lower horizontal beams to reduce weight, and increased the thickness of the beam holding the pin to reduce max stress at that location.

Shown below are images of the mesh and each FEA result. Also shown are my handwritten values and calculations for error estimation.

2a.

<img width="277" height="127" alt="123MeshBig" src="https://github.com/user-attachments/assets/39f8b3c9-4bcd-4400-9746-6eaabf23bb7e" />
<img width="50%" height="970" alt="2aMesh" src="https://github.com/user-attachments/assets/a020df8b-f3ef-48e8-9c52-39ae41d1656f" />
<img width="50%" height="912" alt="2aSF" src="https://github.com/user-attachments/assets/aa684795-807b-438e-88c1-ac46e504e711" />
<img width="50%" height="956" alt="2aStress" src="https://github.com/user-attachments/assets/f2a4fb8e-a72c-4e57-aca2-48287fcb074e" />
<img width="50%" height="927" alt="2aDef" src="https://github.com/user-attachments/assets/0c481a35-8a1a-4c30-9705-9257159e1105" />

2b.

<img width="276" height="137" alt="123MeshMed" src="https://github.com/user-attachments/assets/a4910ad0-c547-4b1f-8f0b-af2a19d0f640" />
<img width="50%" height="913" alt="2bMesh" src="https://github.com/user-attachments/assets/b7cbc1c8-26b2-4666-9ed2-d501d1b8f297" />
<img width="50%" height="917" alt="2bSF" src="https://github.com/user-attachments/assets/ffc7b96f-d66d-4255-9329-5e56b9981746" />
<img width="50%" height="943" alt="2bStress" src="https://github.com/user-attachments/assets/ed4c271a-a97d-49e7-8df3-165a81f0a63e" />
<img width="50%" height="946" alt="2bDef" src="https://github.com/user-attachments/assets/a1495ba0-b67c-4753-9ed5-2f93d00f7be3" />

2c.

<img width="276" height="130" alt="123MeshSmall" src="https://github.com/user-attachments/assets/c739778d-7071-4280-8db5-4a2cdf92a973" />
<img width="50%" height="926" alt="2cMesh" src="https://github.com/user-attachments/assets/71e122f0-58a5-4840-babf-b88d1be1cabf" />
<img width="50%" height="918" alt="2cSF" src="https://github.com/user-attachments/assets/9b5427f8-dde0-4930-be8f-e5fd89bb1e5b" />
<img width="50%" height="931" alt="2cStress" src="https://github.com/user-attachments/assets/a1b56850-0abb-44ea-b2b3-a2c082500c03" />
<img width="50%" height="935" alt="2cDef" src="https://github.com/user-attachments/assets/527811f2-6813-469d-98ea-4df2ec8f553d" />

My error estimation was above 7% so it did'nt reach convergence, but it was 3 tests.

## Design #3

For the third design I added holes in the top beams and shrank the bottom beam even more to reduce weight, and added fillets on the edges near the pin and each corner to reduce stress.

Shown below are images of the mesh and each FEA result. Also shown are my handwritten values and calculations for error estimation.

3a.

<img width="277" height="127" alt="123MeshBig" src="https://github.com/user-attachments/assets/6ce6a15a-b9a1-4e81-8f2a-36ec8df6620c" />
<img width="50%" height="937" alt="3aMesh" src="https://github.com/user-attachments/assets/6fdf8d82-30c3-40ce-bd2f-74443cb70adb" />
<img width="50%" height="900" alt="3aSF" src="https://github.com/user-attachments/assets/2cc97b71-e8f1-4f34-b607-5aca095d3af5" />
<img width="50%" height="917" alt="3aStress" src="https://github.com/user-attachments/assets/d24301ff-d3e3-4f8e-a893-bb8d466e39bf" />
<img width="50%" height="921" alt="3aDef" src="https://github.com/user-attachments/assets/02ae14c0-e7de-4293-9a73-c9d4207bb677" />

3b.

<img width="276" height="137" alt="123MeshMed" src="https://github.com/user-attachments/assets/89cd8437-6c35-4cd8-83d5-f54d560bf7fb" />
<img width="50%" height="912" alt="3bMesh" src="https://github.com/user-attachments/assets/3394ad30-0830-45d8-a9da-9751740963f4" />
<img width="50%" height="903" alt="3bSF" src="https://github.com/user-attachments/assets/338c2d5b-f2bb-4c59-9b49-6fdf25e40c06" />
<img width="50%" height="938" alt="3bStress" src="https://github.com/user-attachments/assets/08bf3c2e-0e38-46c2-aabb-9ad1702115c4" />
<img width="50%" height="927" alt="3bDef" src="https://github.com/user-attachments/assets/b3f7ec0f-aa9f-419c-8771-36d2fd9ea3ef" />


My error estimation was below 7% so it did reach convergence, after 2 tests.



## Link FEA (MEGR 2157)

## Link Design #1

Completing the same process for the link, I started with my original design for the first run. 

Shown below are images of the mesh and each FEA result. Also shown are my handwritten values and calculations for error estimation.

1a.

<img width="277" height="127" alt="123MeshBig" src="https://github.com/user-attachments/assets/55e2d910-7b30-4c4e-80da-0d970081c133" />
<img width="50%" height="785" alt="l1aMesh" src="https://github.com/user-attachments/assets/9cb75871-4546-43c4-9dc2-db8c79e23772" />
<img width="50%" height="857" alt="l1aSF" src="https://github.com/user-attachments/assets/19e8f7eb-86aa-435c-bf91-5d57535fc9a1" />
<img width="50%" height="941" alt="l1aStress" src="https://github.com/user-attachments/assets/7bfb49e6-045d-409b-9a4e-658f0a7164e7" />
<img width="50%" height="961" alt="l1aDef" src="https://github.com/user-attachments/assets/2335467a-55ee-4ee2-a13a-3aa5d6f5065d" />

1b.

<img width="276" height="137" alt="123MeshMed" src="https://github.com/user-attachments/assets/3b1543cb-46a4-409f-be1b-0e4f08e82214" />
<img width="50%" height="755" alt="l1bMesh" src="https://github.com/user-attachments/assets/7a78a84a-0d05-458e-9c4b-382f370b2016" />
<img width="50%" height="740" alt="l1bSF" src="https://github.com/user-attachments/assets/a4f7c5c6-5898-4720-b414-bf322fefa5f6" />
<img width="50%" height="781" alt="l1bStress" src="https://github.com/user-attachments/assets/e724fc4f-fcfd-4aec-b62d-2a8924b35d74" />
<img width="50%" height="792" alt="l1bDef" src="https://github.com/user-attachments/assets/2d5a187b-8737-4d79-ba50-ce883933d41a" />


My error estimation was below 7% so it did reach convergence, after 2 tests.

## Link Design #2

For my second design I increased the thickness between the larger hole and the outside edge from 2.5in to 3.5in to make it stronger.

Shown below are images of the mesh and each FEA result. Also shown are my handwritten values and calculations for error estimation.

2a.

<img width="277" height="127" alt="123MeshBig" src="https://github.com/user-attachments/assets/7f2d0e37-e731-49e6-95f7-e824454c7109" />
<img width="50%" height="1017" alt="l2aMesh" src="https://github.com/user-attachments/assets/0f803264-b094-4681-86ee-15d19923b16b" />
<img width="50%" height="862" alt="l2aSF" src="https://github.com/user-attachments/assets/ec74b740-0fe2-470f-a783-85c6a15c87f7" />
<img width="50%" height="947" alt="l2aStress" src="https://github.com/user-attachments/assets/eae563b8-a55a-442d-948f-5fd17947b83f" />
<img width="50%" height="941" alt="l2aDef" src="https://github.com/user-attachments/assets/0812c169-0da8-4632-83fd-f8ef0ad37d28" />

2b.

<img width="276" height="137" alt="123MeshMed" src="https://github.com/user-attachments/assets/f86ac279-669e-484e-ba7e-e5133abdc1ef" />
<img width="50%" height="866" alt="l2bMesh" src="https://github.com/user-attachments/assets/f7297f2c-a81e-414d-8055-ac7ddf74d253" />
<img width="50%" height="860" alt="l2bSF" src="https://github.com/user-attachments/assets/cc046d3c-4834-4221-974f-eb4493f9254e" />
<img width="50%" height="697" alt="l2bStress" src="https://github.com/user-attachments/assets/a933f85f-3597-4d8f-a52c-972c0972dbf4" />
<img width="50%" height="658" alt="l2bDef" src="https://github.com/user-attachments/assets/718414f9-fb5f-4cf4-b9a7-64478a2ffba8" />


My error estimation was below 7% so it did reach convergence, after 2 tests.

## Link Design #3

For my third design I decreased the gap between the two holes to reduce unecessary weight.

Shown below are images of the mesh and each FEA result. Also shown are my handwritten values and calculations for error estimation.

3a.

<img width="277" height="127" alt="123MeshBig" src="https://github.com/user-attachments/assets/ee45e0b8-cd6b-4c73-8a92-0d7a5757057a" />
<img width="50%" height="870" alt="l3aMesh" src="https://github.com/user-attachments/assets/45cf4d5a-f5f4-42b2-a9e9-f15c621dc86b" />
<img width="50%" height="863" alt="l3aSF" src="https://github.com/user-attachments/assets/765d5ca4-36ff-4dd6-b0da-5e6ad87ab4b3" />
<img width="50%" height="945" alt="l3aStress" src="https://github.com/user-attachments/assets/4154b5c7-1116-45af-acf9-67694dc706f2" />
<img width="50%" height="928" alt="l3aDef" src="https://github.com/user-attachments/assets/c218b69a-3199-47da-b4a2-eae7f963ade6" />

3b.

<img width="276" height="137" alt="123MeshMed" src="https://github.com/user-attachments/assets/c20a9d13-0867-4520-a668-538ded8ceb6a" />
<img width="50%" height="867" alt="l3bMesh" src="https://github.com/user-attachments/assets/bca647fb-224e-420b-80a1-42969e4ce0bb" />
<img width="50%" height="861" alt="l3bSF" src="https://github.com/user-attachments/assets/45a5faf5-403c-4706-81c5-65f8d8c82406" />
<img width="50%" height="917" alt="l3bStress" src="https://github.com/user-attachments/assets/7f4e207e-f374-4867-b784-cff7ce12fe59" />
<img width="50%" height="940" alt="l3bDef" src="https://github.com/user-attachments/assets/5cf2306d-2d29-417d-af04-2d57ef25eb94" />


My error estimation was below 7% so it did reach convergence, after 2 tests.


<a href="https://github.com/tmansou1/megr2157-portfolio/raw/refs/heads/main/A6_Bracket.SLDPRT" download>Download CAD Bracket Design #1</a>

<a href="https://github.com/tmansou1/megr2157-portfolio/raw/refs/heads/main/A7_Design2.SLDPRT" download>Download CAD Bracket Design #2</a>

<a href="https://github.com/tmansou1/megr2157-portfolio/raw/refs/heads/main/A7_Design3.SLDPRT" download>Download CAD Bracket Design #3</a>

<a href="https://github.com/tmansou1/megr2157-portfolio/raw/refs/heads/main/A7_LinkDesign.SLDPRT" download>Download CAD Link Design #1</a>

<a href="https://github.com/tmansou1/megr2157-portfolio/raw/refs/heads/main/A7_LinkDesign2.SLDPRT" download>Download CAD Link Design #2</a>

<a href="https://github.com/tmansou1/megr2157-portfolio/raw/refs/heads/main/A7_LinkDesign3.SLDPRT" download>Download CAD Link Design #3</a>
