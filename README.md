# Roles-Large-Agile-Teams
Roles within a large agile team
## Introduction
These teams are composed of 20 or more members. The strategy within these teams is to organize the larger team into a collection of smaller teams. Each subteam will be responsible for one or more subsystems. This allows them to work as a small agile team responsible for delivering working software in a timely manner. 

## Additional Roles for a large agile team
1. Architecture Owner
- Responsible for facilitating architectural decisions on a sub-team and is part of the architecture owner team which is responsible for overall architectural direction of the project. Architecture owner team starts off by thinking about architetural envisioning for their sub-systems and for the system as a whole. They not only set the architectural direction, but they also facilitate its creation and evolution.

2. Integrator
- This role is responsible for building the entire system from its many subsystems. The larger the overall team is, the larger and more complicated the system being built. There could be more than one integrator throughout the overall team. The people on this team usually work closely with the independent test team. 

## Critical Issues large agile teams need to coordinate
1. Project Management Activities
- This team is sometimes called the program management team. It is comprised of the team leads from the various subteams. Their goal is to coordinate the management aspects of the overall team. They will have daily meetings referred to as "scrum of scrums", where current status is shared and issues are identified. 

2. Technical/Architectural Issues
- At the start of the project this team is responsible for architectural envisioning to identify the initial technical direction and provide a basis for organizing the subteams. In the first week or so of the project, their goal is to identify the subsystems and their interfaces, a strategy called "managing to the seams." Once the interfaces are well defined it is possible for the individual subteams to focus on implementing the innards of those subsystems. Throughout the project this team will meet on a regular basis to share ideas and resolve technical issues. 

3. Requirements/Project Ownership Issues
- Product ownership team is comprised of the product owners of each subteam and is resposible for coordinating the requirements effort across the subteams. They will need to negotiate requirements with the larger body of stakholders they represent. They will also need negotiate the disputes between subteams as to who should do what and what a requirement actually means. They strive to minimize overlapping work between subteams. 

4. System Integration
- System integration occurs throughout the entire agile lifecycle, not just at the end of the project. During the "Elaboration Phase" an important goal is for the subteams to make mocks of their subsystems according to the interface specifications agreed to earlier. The goal is to do a complete end-to-end build of the mocked out system to ensure that the subteams are working to the same technical vision. 
One of the advanatges for creating a mock system is so the individual subteams can now move forward with few dependencies on other subteams. Each team will evolve their subsystems replacing the mock version of code with real code. These versions are then sent to the other subteams who then choose when they want to integrate these new versions into their own environment. Another advantage is that your test team can now test against the entire model. You can put together your integration framework to support your integration efforts across the entire system as well as integration efforts on individual subteams. Individual subteams will promote their code after they've tested it within their own environments. A test team will often do a full system integration test, this might be difficult for the subteams to do becuase of time and resource constraints. 

## Diagram of what a large agile team looks like:

Citation: http://www.ambysoft.com/essays/agileRoles.html
