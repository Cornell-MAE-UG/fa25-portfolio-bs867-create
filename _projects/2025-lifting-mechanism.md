---
layout: project
title: Lifting Mechanism Design
description: Statics and Mechanics of Solids design of a lifting mechanism usign a linear actuator, a rigid bar and three pins wihtin a space of 150 cm wide by 50 cm tall
images: /assets/images/HW 4- Portfolio Design.jpg
        /assets/images/HW 4- Calculations.jpg
---
**Step 1:**

**Problem Definition, Constraints, Degrees of Freedom:**

For my Statics and Mechanics of Solids class, we were instructed to make a lifting mechanism. Our constraints were to keep our design within a 2D space of 150 cm wide by 50 cm tall. Our design had to remain in static equilibrium. We were allowed to use a linear actuator that we chose from an [online catalog](https://www.tolomatic.com/wp-content/uploads/2022/05/2700-4000_29_IMA_cat.pdf), a rigid linear bar that could have any length, as long as it stayed within the constrained space, and three pins. Two of these pins had to be pinned on the ground. My stroke length, H<sub>lift</sub> has to remain within the total 50 cm height constraint. Since this is a 2D deisgn, this design has 3 degrees of freedom.  

**Static Analysis:**

My design uses the linear actuator- IMA 33 MV43 which has a max force of 11.1 kiloNewtons(kN). The bar was already lifted an initial height of 21.52 centimeters(cm) due to the initial height of the base of the linear actuator. The left edge of the bar is connected by a pin suport to the left side of the space we're given and the linear actuator is pinned all the way at the right edge of the space. The last pin is one between the end of the linear actuator's piston that extends and the linear bar. Please refer to the image at the beginning to get a visual of the design space.

<img src="{{ '/assets/images/HW 4-Portfolio-Design.jpg' | relative_url }}" alt="HW 4 Portfolio Design" width="500">

The following image contains all my work as to how I calculated the amount of allowable weight this lifitng mechanism can support. 

<img src="{{ '/assets/images/HW 4-Calculations.jpg' | relative_url }}" alt="HW 4 Portfolio Design" width="500">

**Step 2:**

**Maximum Deflection and Beam Design:**

I will now consider if my beam if not rigid and it can bend due to the applied vertical force of the actuator. I used the W<sub>max</sub> I found in my previous step. I created equations to find V(x), the shear force throughout the beam, which I found to be constant, and M(x), the internal moment throughout the beam. I then integrated my found M(x) equation twice to find the delection equation. This is from the formula EIy(x)"=M(x), where E is a material property, and I is dependent on the shape I will later choose. I then took the derivative of y(x), y'(x), to see where y'(x)=0, to find the maximum deflection, which I found to be L/√3. Below is an image of my calculations and specific analysis. 

<img src="{{ '/assets/images/HW 12- Beam Deflection.jpg' | relative_url }}" alt="HW 12 Beam Deflection" width="500">

Additionally, I cannot have my beam deflect more than 2% of its total length, which for my beam is 2.8 cm. I chose my beam to be made out of a titanium alloy (6% Aluminum, 4% Vanadium). Its modulus of elasticity is 115 gigapascals, and its density is 4730 kg/m<sup>3</sup>. Out of materials in our textbook's materials properties list, I found this one to be a good middle value for the elasticity modulus and density. From there I used the maximum deflection equation in the image above to solve for the smallest moment of iniertia possible. For the shape of my beam, I decided a hollow square would be a stable cross section, while also minimizing my cross section area to keep the mass of the beam lower. I solved the moment of inertia equation for the thickness and set it equal to the smallest value it could be and still maintain the minimum deflection. Ultimately, my beam cross section was 65mm x 65mm x 3.7mm, where the outer sides are 65mm and the thickness of the beam if 3.7mm. The weight of this beam is 6.008 kg. Below is my final beam design. 

<img src="{{ '/assets/images/HW 12- Beam Design.jpg' | relative_url }}" alt="HW 12 Beam Design" width="500">