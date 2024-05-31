# GEP-01 Release Zero 
_Non functional Epic, definition of technologies and methodologies. First deploy_

## General Description

The purpose of this epic is to analyze, define, and document all the non-functional decisions that needs to be made in order to develop, test, and deploy the entire scope of the application.

The second objective is, after defining technologies and environments, to mount all the layers of the application in the cloud for online access in all environments (or at least in production).

As a result of all of this, it is expected to have different documents containing all this information. This documents will be used as reference during all the project life cycle.

## User Stories
|US Code|US Name|Description|
|:--:|--|--|
|[GUS-01](GUS-01-Architectural-Design.md)|Architectural Design| General Architecture design, technologies definition |
|[GUS-02](GUS-02-Environments-Definition.md)|Environments Definition| Environments definition, deploy process definition, deploy plataform definition |
|[GUS-03](GUS-03-Repositories-Definition.md)|Repositories Definition| GIT server provider selection, versioning flow definition, repositories creation |
|[GUS-04](GUS-04-Methodology-Management.md)|Methodology and management| Methodology selection, SDLC Definition, management tool selection, Project creation |
|[GUS-05](GUS-05-Splash-Page.md)|Splash page online| Splash page creation and deploy |
|[GUS-06](GUS-06-Health-API.md)|Health or ping API endpoint| Healthcheck API creation and deploy |
|[GUS-07](GUS-07-Database-Access.md)|Database access| Database creation and deploy |

## Dependencies

None

## Acceptance Criteria
* As a team we have access to the Architectural Design Document
* As a team we have access to the Environment Definition Document
* As a team we have access to all the environments on all application layers
* As a team we have access to the Code Repositories
* As a team we have access to the Project management tool
* As a user you have access to the Application splash screen on the production environment
* All user stories corresponding to this epic are completed

Aditionally remember that all epics must also comply the [General Acceptance Criteria](../generalAcceptanceCriteria.md)

## Definition of Done
The following conditions must be meet to consider this epic as done:
* All associated user stories have been implemented, tested, and meet their respective acceptance and Definitions of Done.
* Integration Testing: The functionality and interactions between the associated user stories (and between previously implemented functionalities) have been thoroughly tested to ensure that they work together seamlessly.
* Acceptance Testing: The epic has undergone acceptance testing with stakeholders or end users to validate that it meets their requirements and expectations.
* Code Review: The code related to the epic has undergone code review, and any identified issues or feedback has been addressed.
* Demonstration: The epic has been presented or demonstrated to stakeholders or the product owner to showcase the implemented functionality and gather feedback.
* Production Release: All the features described on the user stories are deployed on the production environment.

---
[Back to Index](../../README.md)

