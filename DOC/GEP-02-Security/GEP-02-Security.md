# GEP-02 Security 
_Authentication and Users definition_

## General Description

The purpose of this epic is to implement the Authentication and Autorization mechanisms defined on the [Architectual Design](/DOC/GEP-01-Release-Zero/GUS-01-Architectural-Design.md).

The following features are expeted:
* Users definition
* Login Page
* Main Page with logged user information
* Backend Security Endpoints

## User Stories
|US Code|US Name|Description|
|:--:|--|--|
|[GUS-08](GUS-08-Users-Definition.md)|Users Definition|Users list, types of users, and users data definition|
|[GUS-09](GUS-09-Authentication-API.md)|Authentication API|Authentication API endpoints|
|[GUS-10](GUS-10-Login-Page.md)|Login Page|Login Page|
|[GUS-11](GUS-11-Main-Page.md)|Main Page|Main Page with logged user information|


## Dependencies

The security implementation, environments and infraestructure defined on [Release Zero](/DOC/GEP-01-Release-Zero/GEP-01-Release-Zero.md) are hard dependencies on this epic.

## Acceptance Criteria
* As an application user I have the means to authenticate myself.
* As an authenticaded user I have access to the main page showing the navigation controls and my personal information.
* As any defined user I can login successfully to the application.

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

