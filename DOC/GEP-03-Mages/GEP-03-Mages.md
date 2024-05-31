# GEP-03 Mages
_Clients Management_

## General Description

The purpose of this epic is to implement all the necesary features to do a proper clients management

The following features are expeted:
* New Mage
* Modify existing Mage
* Mages List
* Data Migration

## User Stories
|US Code|US Name|Description|
|:--:|--|--|
|[GUS-12](GUS-12-New-Mage.md)|New Mage|New mage creation in the application|
|[GUS-13](GUS-13-Mages-List.md)|Mages List|Mages List with search funcionalities|
|[GUS-14](GUS-14-Modify-Mage.md)|Modify Mage|Modify existing mage data|
 [GUS-15](GUS-15-Mages-Migration.md)|Mages Migration|Migration of mages data from a previous system|

## Dependencies

None.

## Acceptance Criteria
* As an authenticated Overseer or Minion user I have the means to list all mages and search for a particular mage.
* As an authenticaded Overseer user I can create a new mage.
* As an authenticaded Overseer user I can modify an existing mage.
* As an authenticated Overseer or Minion user I can find the mages from the previous system.


Aditionally remember that all epics must also comply the [General Acceptance Criteria](../generalAcceptanceCriteria.md)

## Definition of Done
The following conditions must be meet to consider this epic as done:
* All the created components must be deployed.
* All associated user stories have been implemented, tested, and meet their respective acceptance and Definitions of Done.
* Integration Testing: The functionality and interactions between the associated user stories (and between previously implemented functionalities) have been thoroughly tested to ensure that they work together seamlessly.
* Acceptance Testing: The epic has undergone acceptance testing with stakeholders or end users to validate that it meets their requirements and expectations.
* Code Review: The code related to the epic has undergone code review, and any identified issues or feedback has been addressed.
* Demonstration: The epic has been presented or demonstrated to stakeholders or the product owner to showcase the implemented functionality and gather feedback.
* Production Release: All the features described on the user stories are deployed on the production environment.

---
[Back to Index](../../README.md)

