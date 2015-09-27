# Developer Handbook
This document outlines all of the functions, rules and tasks that are given to developer and should be followed. Additionally, this outlines the steps taken to interact with the developers and submit project requests.

### Contribution Policy 
##### The roles of the branches goes as following
- **Master** - This is the official code that has been accepted by all the developers and will be used during competitions.
- **Staging** - This is all code that has been contributed through a pull request but is currently is in testing and has no known bugs. This will always be ahead of master and forked off of the master branch.
- **All Other Branches** - These are personal branches created so the developer can go out and test their code. This should be branched off of staging and synced with staging. Code here may be broken and in order to be merged into staging must have no known issues.

##### How to Contribute
To commit your branch into staging you must first create a pull request. The pull request must state what the function of the code is and why you have made all your changes. To have your pull request merged in it must be 100% functional and up to spec. Deviation from this may result in a denial of merging. The code may only be merged into master by the lead dev and staging may be merged in by any admins. 

### Developer Roles
*Roles are only in place to create order and ensure the code is being written at an effective pace and the software stays organized. In no way does this impose superiority as each member of the developer team has equal opinion and decision making power as the other. This is purely based off of team seniority and coding experience.* 
- **Head Developer**: Brandon Barker
  1. Can Merge code into the Master Branch.
  2. Sets the style used in the code.
  3. Tracks project progress.
  4. Prioritizes certain projects or components of the software
  5. Assumes all abilities and functions of *senior developer*.
- **Senior Developer**: Vishwa Shanmugam
  1. Can merge code into staging.
  2. Designs broader architecture of the software.
  3. Can create pull requests for the master branch,
  4. Can delegate tasks to other *developer(s)*.
  5. Assumes all abilities and functions of *developer*
- **Developer**: John Hofbauer, Sidharth Rajesh, Kavish Saini, Karthik Imayavaramban
  1. Can create new branches off of staging.
  2. Can create pull requests for staging.
  3. Contributes code to the project.
  4. Installs the Jar to the robot.
  5. Creates coding architecture for their specific component which confines to all other predefined rules.
