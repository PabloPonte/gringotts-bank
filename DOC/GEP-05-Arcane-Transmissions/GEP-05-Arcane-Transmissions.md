# GEP-05 Arcane Transmissions
_Transfers Between Accounts_

## General Description

The purpose of this epic is to implement the Arcane Transmission operation.

The following features are expected:
* Operation: Arcane Transmission (Transfer)

## User Stories
|US Code|US Name|Description|
|:--:|--|--|
|[GUS-19](GUS-19-Operation-Arcane-Transmissions.md)|Operation: Arcane Transmission|Transfers between accounts|

## Dependencies

Due to components dependencies, the [Accounts Epic](../GEP-04-Accounts/GEP-04-Accounts.md) must be completed to implement this epic.

## Acceptance Criteria
* As an authenticated Overseer or Minion user, I can perform the Arcane Transmission operation.
* As an authenticated Overseer or Minion user, I can view the Arcane Transmission related transactions in the transaction history for a particular mage.
* All validations for this operation are properly implemented.

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

