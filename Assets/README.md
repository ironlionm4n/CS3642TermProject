# Introduction
Amber Alert algorithm which predicts the traveling path of the suspect vehicle.

## Prerequisites
Unity Editor Version 2022.3.8

### Contact Information
Mikail Miller  
Kelvien Pyryt

---
### Problem Trying to Solve
The Amber Alert service is a public service announcement warning other members of the community  
of a child abduction and the last known vehicle being driven by the suspect. This warning allows others  
to warn the local law enforcement the location of the vehicle.  
  
The downfall of this alert: people not paying attention, an alert was not received, etc.

---
### Proposed Solution
Utilize traffic cameras at road intersections to:  

1. Detect the suspect's car using
	1. License plate
	2. Car model
	3. Color
2. Determine direction the car is heading.
3. Record previous traffic camera detections.

Use AI to determine both the car's general location and predicted direction. This will be communicated  
to local law enforcement.

The agent will utitlize the **car's detection history** and the **Georgia road map** for calculations.  
*Should we use machine learning for the agent to better understand car patterns?*



