# A3 – Parametric and FEA

## Objective

To design a bar which has a circular cross section where the values of the criteria given for the material, maximum deflection, and load. Determine the bar’s minimum geometry (ie.. length, diameter, and weight) through parametric design while under direct tension. Then verify the geometry through finite element analysis.

## Design

For my bar design I chose a force of 400lbs and a diameter of 0.5in. The aluminium alloy I chose was 6061 T6 in solidworks which has a Young’s Modulus of 10^7 psi. The max axial deflection was given as 0.009in. Using the direct tension elongation equation and rearranging to solve for L parametrically in solidworks, I got 44.18in.

<img width="50%" height="1485" alt="IMG_0734" src="https://github.com/user-attachments/assets/61c9376c-faa1-4cc4-b0cd-435fbc4cdd4e" />


Shown below are the variables and equations used to parametrically solve for the length.

<img width="50%" height="413" alt="solidworks eqns" src="https://github.com/user-attachments/assets/7b72a2af-775c-4225-83ec-50800238286c" />


## Solidworks FEA

I connected one end of the bar to a support and added the 400lb force pulling the bar on the other end. Below are the deflection map and the von Mises stress map from the FEA.

<img width="50%" height="652" alt="Displacement A3" src="https://github.com/user-attachments/assets/898f6c56-8b61-46cd-bfa5-54f61c3dcb98" />

<img width="50%" height="666" alt="von Mises A3" src="https://github.com/user-attachments/assets/3052ab09-b414-4ff4-b720-e058cfd31de1" />


The maximum stress simulated using the von Mises stress map was 1.563*10^7N/m^2 or 2266 psi. Using 40ksi as the yield strength I got a safety factor of 17.65 which is more than enough.

## Design Reflection

The max axial deflection was given as 0.009in and using solidworks FEA I was able to determine the max displacement to be 0.2284mm which is 0.00899in. The two values are essentially the same, which is expected because the hand calculation used the direct tension elongation equation and this bar has a perfect axial force. I trust the solidworks design and FEA more because it uses global variables while I could have rounded.

_If there were a large pin hole near the side where the bar is attached, estimate the peak stress at the hole and state whether it passes my safety factor._

I was unable to find the stress concentration factor for a hole in a circular bar under tension, so for this question alone I will assume the bar is rectangular with side dimensions equal to the diameter of the bar. Assuming the dimensions of the hole; the diameter is equal to half the width of the bar. Using the equations I found for Kt and the max stress, I was able to determine the max stress to be 6908psi which falls well under the yield strength of 40ksi.

<img width="50%" height="2388" alt="IMG_0732" src="https://github.com/user-attachments/assets/0b4bd843-433e-45c3-b1ff-0b5efed5fa3f" />


## Modify Design Parameters(MEGR 2157)

I changed the max deflection, cross sectional area, and force applied to test whether the length will increase or decrease. I predicted that increasing either the area or deflection would increase the length of the bar, and increasing the force applied would decrease the length. After calculating with different values I was able to confirm my prediction.

<img width="50%" height="1068" alt="IMG_0733" src="https://github.com/user-attachments/assets/d95b5f1b-1c59-4efc-bc1b-d0d6141cbc22" />




