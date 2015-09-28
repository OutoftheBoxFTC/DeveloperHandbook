# A easier way to do X

**Date of Submission:** 4-20-2015

**Background Info/Context:** We were operating in Teleop mode and our robot was doing This thing, That thing, and our robot was in Z mode. Some likely triggers to this failure were the fact that This thing is too memory intensive, leading to X failure. 

**Motivation of Change:** We do Y often and it becomes very tedeious. By making the change to do X we would save a large amount of time and would be able to preform better.

**Required before Development:** Before coding can start we need to build W so that the robot can interface with the input. Until then the code cannot be effiecently deployed. Also, the code for the main drive train has not been completed so we can not complete the aditional code till that is finished.

**Optional or Required:** Optional/Required

**Gamemode** *(Endgame, Autonomous, Tele-Op)*: Endgame

**Functionality/Flow:**
- Main Flow
  * User moves X on the X or Y axis
  * Calculate the direction of joystick
  * Move the robot in Z with a powermultiplier based off of distance from 0, 0
  * Update on joystick movement
- Alternative Flow
  * When the A button is heald
    1. Half the power multiplier
    2. Slows down the robot by half
  * When the B button is heald
  	1. Double the power multiplier
  	2. Doubles the robot speed
  