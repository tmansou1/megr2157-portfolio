# A2 – Truss Stress Analysis

## Objective

-Design a lightweight planar truss using A500 steel or an alternative material.(A36 steel)

-Create free body diagrams (FBDs) for joints and critical pins.

-Calculate the required cross-sectional area of truss elements with a safety factor.

-Determine pin sizes based on shear forces with a safety factor.

-Solve equations symbolically and numerically for both truss and pin design.

-Estimate the total weight of the truss and pins.

-Create a CAD model with accurate dimensions and connections.

-Compare CAD weight predictions with hand calculations.

-Document key engineering lessons learned from the process.

The goal is to determine the minimum weight with safety factors of 3.5 and 4 for the members and pins respectively. Point A is a pin joint and point B is a roller joint. The two forces P, applied at points C and D, were chosen to be 20kN each. The closest steel to A500 that I could find in Solidworks was A36 steel which has a yield strength of 250MPa. 

<img width="420" height="271" alt="truss structure" src="https://github.com/user-attachments/assets/e457afca-1a6b-42f3-bab6-51493b603f62" />



## Analyze
**Truss geometry**

I chose my design because adding point F in between points A and B allows me to create a simple truss with three triangles all connected. With 5 points, 7 members are needed to be exactly triangulated.
The image below shows the truss design including dimensions and angles. The external forces A_y and B_y were solved for.

<img width="50%" height="2697" alt="IMG_0700" src="https://github.com/user-attachments/assets/34eb9412-6f06-4366-b8a8-a4afe5d67fe0" />

Below are all the FBDs for each pin, solving for the internal forces.

<img width="50%" height="2680" alt="IMG_0701" src="https://github.com/user-attachments/assets/7fb265bb-17f1-4175-b00d-8b35a2f8646e" />

Solving the FBD for pin F was just to confirm that the other internal forces are correct.

<img width="50%" height="2393" alt="IMG_0702" src="https://github.com/user-attachments/assets/e7f4f47c-3b51-43d4-a52c-f6bd9ef57b16" />

I then used the largest internal force and a safety factor of 3.5 to calculate the required cross sectional area for the members. I decided to have the cross sectional area be a square for simplicity. Using a given density for A36 steel and the newly found area, I added up the whole volume and multiplied by the density to find the weight of the whole truss(not including pins).

<img width="50%" height="1815" alt="IMG_0703" src="https://github.com/user-attachments/assets/6421767b-e0ba-46fb-9b9c-466e4b7a47fd" />

For the pins I used the given density, shear yield strength, and a safety factor of 4 to determine the required cross sectional area. For the length of the pins I doubled the width of the truss. After calculating the weight of the pins and adding them to the weight of the truss I got 57.48N and my CAD model with appropriate mass settings gave me a weight of 46.46N. I believe the main reason for the difference in weights is due to the members and pins overlapping at each joint, while another reason could be rounding errors.

<img width="50%" height="2831" alt="IMG_0705" src="https://github.com/user-attachments/assets/4aa4a5fa-2dee-4fe7-bd01-a0b9908f14de" />
<img width="50%" height="965" alt="Screenshot 2026-09-01 182104" src="https://github.com/user-attachments/assets/97b63b70-5562-403c-b7e9-df189042ee31" />


### Likelihood of Failure Modes in Truss Components (MEGR 2157)
**Truss members**

Member CD is a zero force member and therefore cannot fail unless the applied forces change. Members BC, AF, and CF are all in compression. The expected failure mode for these members is buckling, because they are long and skinny compared to short and thick. Members BF, AD, and DF are all in tension. The expected failure mode for these members is yielding, because the material they’re made of is ductile and stretches some before fracturing. The material, A36 steel, is ductile because it can stretch 20% before breaking, compared to a brittle material like ceramic that could only stretch 0.1%. A possible solution to these problems could be using a stronger metal with a relatively same density, for example titanium.

**Pin connections**

The pins will likely fail due to direct shear, because the load is applied directly perpendicular to the length of the pins. Hardened tool steel has a high yield shear strength from its hardening but it also decreases its toughness, this can cause a sudden snap or shear fracture instead of slow bending. A solution to this failure would be to make the pin double-shear instead of single-shear to spread the force.



## Decide
_Which geometry did you select, and why? This is your first open design choice in the course — defend it._

I chose a simple geometry of three triangles because is it the minimum stable geometry. A planar truss is only statically determinate when the number of members satisfies m = 2n - 3 where m is the number of members and n is the number of joints, I have 5 pins and 7 members. Adding extra members could add unnecessary weight and also make the calculations harder.

## Communicate

**Engineering lesson learned**

I learned how to design a simple truss while using safety factors to determine appropriate sizes for the cross sectional area of the truss and the pins. I also learned how different failure modes can affect a truss, and why.

I spent roughly 7 hours on this assignment.

Sources

https://www.metalsupermarkets.com/grade-guide-a36-steel 

https://www.edconsteel.com.au/articles/steel-and-metal-articles/hardness-vs-toughness-tool-steel 

<a href="Truss_with_Pins.SLDPRT" download>Download CAD file</a>
