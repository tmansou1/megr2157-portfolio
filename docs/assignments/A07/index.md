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


My error estimation was above 7% so it did'nt reach convergence, but it was 3 tests.

## Design #2

For my second design I shrank the thickness of the upper and lower horizontal beams to reduce weight, and increased the thickness of the beam holding the pin to reduce max stress at that location.

Shown below are images of the mesh and each FEA result. Also shown are my handwritten values and calculations for error estimation.


My error estimation was above 7% so it did'nt reach convergence, but it was 3 tests.

## Design #3

For the third design I added holes in the top beams and shrank the bottom beam even more to reduce weight, and added fillets on the edges near the pin and each corner to reduce stress.

Shown below are images of the mesh and each FEA result. Also shown are my handwritten values and calculations for error estimation.


My error estimation was below 7% so it did reach convergence, after 2 tests.



## Link FEA (MEGR 2157)

Completing the same process for the link, I started with my original design for the first run. 


<a href="https://github.com/tmansou1/megr2157-portfolio/raw/refs/heads/main/A4_MotorMount.SLDPRT" download>Download CAD Bracket Design #1</a>

<a href="https://github.com/tmansou1/megr2157-portfolio/raw/refs/heads/main/A4_MotorMount.SLDPRT" download>Download CAD Bracket Design #2</a>

<a href="https://github.com/tmansou1/megr2157-portfolio/raw/refs/heads/main/A4_MotorMount.SLDPRT" download>Download CAD Bracket Design #3</a>

<a href="https://github.com/tmansou1/megr2157-portfolio/raw/refs/heads/main/A4_MotorMount.SLDPRT" download>Download CAD Link Design #1</a>

<a href="https://github.com/tmansou1/megr2157-portfolio/raw/refs/heads/main/A4_MotorMount.SLDPRT" download>Download CAD Link Design #2</a>

<a href="https://github.com/tmansou1/megr2157-portfolio/raw/refs/heads/main/A4_MotorMount.SLDPRT" download>Download CAD Link Design #2</a>
