# GUS-03 Repositories Definition
_GIT server provider selection, versioning flow definition, repositories creation_

## Definition
As a development team, we want to create all the GIT repositories needed to ensure the proper code versioning of the project.

## Details
To achieve this objective, three issues must be addressed:
* Repositories design: determine the number of repositories to be created and which parts of the codebase will be included on each.
* Server selection and creation: 
    * Decide which remote server/vendor will be used to host the remote GIT repository.
    * Create the repositories.
    * Create and/or assign all users to each repository with their corresponding roles and permissions.
* Define a versioning flow or branching strategy

```
Suggestions 

Any GIT remote server provider will work fine to host just the repositories. GitHub and GitLab are the most popular choices. 

Ensure that the project visibility is correct.

Monorepo vs Multirepo is a big debate, each option has their pros and cons, for a less experienced team a multirepo approach is recommended. 

In this scenario the recommended repos are:
* Web App: containing the code for the frontend application
* Web Api: containing the code for the backend application
* Database: containing the code for the database structures
* Automation: containing the code for the all the automated tests
```

## Dependencies
None

## Acceptance Criteria
* As a team we have access to all the repositories created with read permissions.
* Each team member have their corresponding role and permissions granted.
* As a team we know and understand the flow or branching strategy that will be used to version the project properly.

Aditionally remember that all user stories must also comply the [General Acceptance Criteria](../generalAcceptanceCriteria.md)

## Definition of Done
The following conditions must be meet to consider this user story as done:
* The remote GIT repositories are created.
* All team members have access with their corresponding roles and permissions.
* The branching strategy is defined and comunicated to all team members.

---
[Back to Epic](GEP-01-Release-Zero.md) <br>
[Back to Index](../../README.md)