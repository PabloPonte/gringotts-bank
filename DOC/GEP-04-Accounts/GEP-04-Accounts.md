# GEP-04 Accounts
_Mages Accounts Management_

## General Description

The purpose of this epic is to define how the mage's accounts work and implement a set of features related to the operations that can be made. 

The following features are expected:
* Account Balance
* Account Transactions History
* Operation: Magical Placement (Deposit)
* Operation: Magical Retrieval (Withdraw)

The migrated mages must have their corresponding balances migrated as well.

## User Stories
|US Code|US Name|Description|
|:--:|--|--|
|[GUS-16](GUS-16-Account-Balance.md)|Account Balance|Account definition and balance calculation|
|[GUS-17](GUS-17-Transactions-History.md)|Transactions History|Detailed chronological list of all historical transactions|
|[GUS-18](GUS-18-Account-Operations.md)|Account Operations|Magical Placements (Deposits) and Magical Retrieval (Withdraws)|

## Dependencies

Due to components dependencies, the [Mages Epic](../GEP-03-Mages/GEP-03-Mages.md) must be completed to implement this epic.

## Acceptance Criteria
* As an authenticated Overseer or Minion user, I can see the current account balance for a particular mage.
* As an authenticated Overseer or Minion user, I can see the complete operation history for a particular mage account.
* As an authenticated Overseer or Minion user, I can perform the Magical Placement operation on a mage account.
* As an authenticated Overseer or Minion user, I can perform the Magical Retrieval operation on a mage account.
* The migrated mages have their balances migrated as well.

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

