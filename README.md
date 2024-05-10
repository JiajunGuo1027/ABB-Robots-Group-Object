# ABB-Robots-Group-Object
Program an industrial robot (either the IRB1660 or IRB140) to guide a simulated glue dispenser around the edge of an injection molded part. 
The "images" folder shows the running results and the designed jig.

## Task
Aim: To use the industrial robot to simulate the application of sealant to a complex object (‘the workpiece’), so as to apply the 'sealant' correctly in the minimum time.

The total program cycle should include the following:
1. Conveyor Wait Time
2. Start from Home
3. Pick Tool (or simulate pick up tool)
4. Navigate workpiece (application of the 'sealant')
5. Place Tool (or simulate place tool)
6. Display appropriate messages
7. Return to Home

## Run
Use the TCP(Tool Centre Point) 'Crytool' and the Workobject 'Crywobj'

The Program name is 'Crystal Mech'

Then Click 'Debug' -> 'PP to main' -> 'Run'
