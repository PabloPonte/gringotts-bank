# GEP-06 Mystical Insights
_Different business metrics_

## General Description

The purpose of this epic is to implement a metrics dashboard for the Overseer.

The following features are expected:
* Overseer Dashboard
* Account Balance History Graph

## User Stories
|US Code|US Name|Description|
|:--:|--|--|
|[GUS-20](GUS-20-Overseer-Dashboard.md)|Overseer Dashboard|A dashboard with serveral metrics|
|[GUS-21](GUS-21-Account-Balance-Histogram.md)|Account Balance Histogram|Account Balance History Graph on the Mage Detail page|

## Dependencies

Due to components dependencies, the [Arcane Transmissions](../GEP-05-Arcane-Transmissions/GEP-05-Arcane-Transmissions.md) must be completed to implement this epic.

## Acceptance Criteria
* As an authenticated Overseer user, I have access to the Metrics Dashboard.
* As an authenticated Overseer or Minion user, I can view the Account Balance History Graph on the Mage Detail Page.

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

