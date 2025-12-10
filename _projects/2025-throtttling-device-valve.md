---
layout: project
title: Throttling Device Valve Breakdown 
description: Breakdown of a thermal device, how it works, and relevant equations
image: /assets/images/Real-Throttle.png
---
In Thermodyanmics, we have discussed many different devices, their functions, and what settings they are best used for. As part of an assignment, I wil break down the functions of a throttling device valve and an example of an operating condition we can change that would lead to a change to how we analyze the device. 

The primary function of a throttling device is to quickly reduce the pressure by a significant amount by restricting or limiting the flow in some way. There is only one inlet and outlet, therefore, a consistent mass flow per unit time. There is no work done on the fluid or created by the valve, since just there's simply some type of restriction introduced in the path of a mass flow(usually liquid or gas) that quickly reduces the pressure. Throttling valves are commonly used in refrigeration systems for example to reduce the pressure of refrigerant at the exit of a condenser to lower pressure to go into an evaporator. Below are diagrams of some different throttle valves as well as the cross section of a valve. 

<img src="{{ '/assets/images/Diff-Throttles.jpg' | relative_url }}" alt="Diff Throttles" width="500">

<img src="{{ '/assets/images/Real-Throttle.png' | relative_url }}" alt="Real Throttle" width="500">

When making the key equations to analyze the throttle valve, I will make the following common assumptions- the valve is operating in steady state(properties such as temperature and pressure don't change with time, constant mass flow, no change in the internal energy of a system), it is adiabatic(no heat transfer in or out of the system), no work(no input shaft/electrical work, no work produced), and kinetic and potential energy changes are negligible. Additionally, throttling device valves are irreversible processes due to the unrestrained expansion(the quick pressure drop), spontaneous mixing of different states as the mass flow will usually be a mix of liquid and vapor during the throttling process and a quick change in phases will be made, and the friction just from the flow of the fluid. The system will be treated as a control volume with a constant mass flow. Below is a system diagram of the valve as well as relevant equations under the stated assumptions. 

<img src="{{ '/assets/images/Throttle-Calc.jpg' | relative_url }}" alt="Throttle Calc" width="500">

An example of an operating condition we could change is the size of restriction that we placed in the flow. If we increase the size of our restriction, then that will result in more resistance to the mass flow therefore a greater pressure drop, and the opposite is true as well, a smaller restriction gives less flow resistance, therefore a smaller pressure drop. A larger pressure drop will result in more of the liquid to turn into vapor, that will also lead to a colder temperature as a byproduct, and vice versa for a smaller pressure drop. There are also consequences if it's too small or too large. If it's too small, then the mass flow may be too restricted that would reduce the efficiency of the system. If it's too large, it may not reach a cold enough temperate or low enough pressure or its liquid to vapor ratio may be too high. 
