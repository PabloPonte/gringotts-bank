# GUS-02 Environments Definition
_Environments definition, deploy process definition, deploy plataform definition_

## Definition
As a development team, we want to create an Environment Definition Document to establish the different environments to develop, test and deploy the production version of the app, as well define the deploy process and plataforms.

## Details

Details that must be defined here:
* Number of environments, names and pourpose for each one.
* Detailed deploy process and actors
* Infrastructure platform
* Pricing model and cost estimation for the selected platforms

This needs to be done for all application layers: front-end, back-end and database 

As a result, the Environment Definition Document must contain all this info including:
* URL or IPs for each environment for each layer
* Credentials for access to each environment
* Credentials and instructions for deployment on each layer and environment


```
Suggestions 

The minimal recommended aproach on environments is:
* Develop
* Testing
* Production

The best approach for the deployment process is to implement a CI/CD automated process, but it requires an experienced team and a well-polished versioning flow. For a less experienced team, a well-documented manual deployment process is a better choice.

As for cloud infrastructure platforms, there are three major providers: AWS, Google Cloud, and Microsoft Azure. Currently, the most popular one is AWS. All three options have free-tiers. However, any of these options can be quite complex for beginners. It is recommended to, at least, do some research on simpler alternatives before deciding which platform to use.
```

## Dependencies
* Some details of the deployment process could have dependencies on the technologies defined on [Architectural Design](GUS-01-Architectural-Design.md)
* The deploy plattaform must support the technologies defined on [Architectural Design](GUS-01-Architectural-Design.md)

## Acceptance Criteria
* As a team we have access to the Environment Definition Document
* The Environment Definition Document includes URLs or IPs to each layer on each environment
* The Environment Definition Document includes credentials to access all environments on all layers
* The Environment Definition Document defines a detailed process to deploy on each environment on all layers
* The Environment Definition Document includes a pricing model and detailed cost estimation for the entire application including all environments and layers 

Aditionally remember that all user stories must also comply the [General Acceptance Criteria](../generalAcceptanceCriteria.md)

## Definition of Done
The following conditions must be meet to consider this user story as done:
* The Environment Definition Document has been reviewed and approved by the development team and stakeholders.
* It is easily accessible to all project team members and stored in a designated location for future reference.
* The Environment Definition Document is aligned with the project's non-functional requirements and overall goals.

---
[Back to Epic](GEP-01-Release-Zero.md) <br>
[Back to Index](../../README.md)