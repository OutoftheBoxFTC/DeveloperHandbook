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
#### Roles
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
- **Developer**: John Hofbauer, Sidharth Rajesh, Kavish Saini, Karthik Imayavaramban, Avi Saini
  1. Can create new branches off of staging.
  2. Can create pull requests for staging.
  3. Contributes code to the project.
  4. Installs the Jar to the robot.
  5. Creates coding architecture for their specific component which confines to all other predefined rules.

#### Cascading Leadership
*Cascading Leadership creates temporary roles based off of who is currently available and/or present at a meeting or event. This is also defined off of urgency and priority of the current task. For instance, if a head developer and/or senior developer is not present at a meeting the head developer/senior developer role will cascade to the next alternative leader.*

- **No Head Developer** → Next Available Senior Developer
  1. Each function and ability will be assumed by the next head developer
  2. This only occurs if the permissions required are involved in a high stakes task.
  3. If the next available senior developer is not available it continues down the leader.
- **No Senior Developer** → The most experienced junior developer assisted and approved by a programming oriented mentor. **||** The head developer.
  1. If the role is assumed by the head developer no other requirements are needed to cascade.
  2. If the role is assumed by a junior developer and mentor there must be a high stake project at hand with an immediate deadline.
  3. The cascaded developer will held responsible for any changes or modifications made to the project.
  4. All other rules are expected to be maintained.
- **No Senior Developer or programming oriented mentor** → The most experienced junior developer.
  1. Any present mentors or adults must elect this developer to make code changes.
  2. This is a worst case scenario and all code changes must be conscious and well thought out.
  3. No major design/code changes may be made. No exceptions.
  4. This code will not be merged into the master/staging branch until a legitimate senior or head developer becomes available.
 - **No Developers** → No code changes can be made.
 
### Task and Tickets
*This is how projects will be assigned and distributed to the developer team. Requests will get vetted and prioritized so that development can occur. Every feature, R&D, and bug is required to go through this task and ticket system.*

#### Submission Types and Steps
- **Bug Submission** - Any error, flaw, failure, or fault in a computer program or system that causes it to produce an incorrect or unexpected result, or to behave in unintended ways. 
  1. Follow the required: [template](https://github.com/OutoftheBoxFTC/DeveloperHandbook/blob/master/templates/bug.md) *(The template does not have to be followed word for word but please provide as much information as possible)* 
  2. Add the "Bug" label upon submission.
  3. The developer assigned to the project is required to verify with the submitter that the bug has been successfully fixed before they may close the ticket.
- **Question** - Any clarification needed for the code or future plans of the code may be submitted as a question and will be answered by an appropriate developer*
  1. There is no template for this; however, please be as forthright as possible  so the developer can answer the question as direct as possible.
  2. A question may only be closed once the poster agrees their question has been answered.
- **Research and Development** - If there is a feature that would be a nice to have for the robot and isn't required for the robots to function this type of ticket would be submitted.
  1. Follow the required: [template](https://github.com/OutoftheBoxFTC/DeveloperHandbook/blob/master/templates/feature.md) *(The template does not have to be followed word for word but please provide as much information as possible)* 
  2. Change the submission type to: **Optional**
  3. Add the "research and development" label upon submission.
  4. If the project is deemed of importance it will be assigned to a developer or will be put on a back-burner for re-evaluation later.
- **Feature** - If there is a feature that would be a nice to have for the robot and isn't required for the robots to function this type of ticket would be submitted.
  1. Follow the required: [template](https://github.com/OutoftheBoxFTC/DeveloperHandbook/blob/master/templates/feature.md) *(The template does not have to be followed word for word but please provide as much information as possible)*
  2. Change the submission type to: **Required**
  3. Add the "Required Feature" label upon submission.
  4. The project will be evaluated, prioritized and then assigned to a developer.

#### Submission Vetting
A ticket will be read by either a head developer or senior developer who will then begin the vetting process. First they will assign one of three priorities:
  1. **Low Priority** - The project does not need to be completed for a decent amount of time.
  2. **Medium Priority** - The project should be actively be worked on for completion; however, there is no immediate rush for completion
  3. **High Priority** - The project will be worked on no matter and is of the utmost important to get pushed into production. 

Once, or if a project has been accepted the senior or head developer will assign a responsible developer. It is the developers responsibility to provide updates to how long a feature will take and the amount of time left till completion. Additionally a ticket has four ways to reach the closed status.
  1. **Failed to Meet Request Specifications** - If  the submitter did not use the templates provided or failed to provide sufficient information
  2. **Wont Fix** - A change or an idea that was decided to not be pursued further
  3. **Duplicate** - If there is an already preexisting ticket
  4. **Completed** - If the ticket submitter agrees the project has been completed the active developer can close it.

#### Submission Life Cycle
*This highlights each step in the life cycle of a ticket and what happens between ticket creation and ticket termination*
  1. First the user must create a new issue: [here](https://github.com/OutoftheBoxFTC/DeveloperHandbook/issues) using one of the stated submission types.
  2. A senior/head developer goes through the un-vetted tickets taking two routes:
    * The ticket is closed and is either re-opened once it has been fixed or stays closed as a mutual agreement between the developer and the submitter
    * The ticket continues on the submission life cycle
  3. The senior/head developer assigns a priority to a ticket and assigns it to the appropriate developer
  4. The developer will make status updates every meeting while working on the ticket communicating with the submitter the status.
  5. The ticket is closed after all parties deem the solution has been put into production or is not viable at the time.