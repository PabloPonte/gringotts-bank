# GUS-01 Architectural Design
_General Architecture design, technologies definition_

## Definition
As a development team, we want to create an architectural design document to establish the technical foundation of the application.

## Details
The following decisions must be made:
* **Front-End Technology**: Choose a technology, language, and/or framework to develop the frontend and the user interface of the application considering the known requirements.
* **Design System or Component Library**: Choose a known design system or a component library to ensure the visualization consistency in all the application.
* **Back-End Technology**: Choose a technology, language, and/or framework to develop the backend of the application considering the known requirements.
* **Database Technology**: Choose a database type, vendor and product to store all the application data considering the known requirements. If you choose a licenced and/or paid product, include the pricing information into the design document. 
* **Security Implementation**: Choose a Authentication and Autorization mechanism to ensure the security of the application.

As a result, the design document must contain a general architectural diagram containing all this components and the connections and interactions between them.


```
Suggestions 

Recommended Front-End technologies:
* Angular (any version except AngularJs)
* React.js
* Vue.js

Recommended Component Libraries:
* Material UI
* Tailwind CSS
* Bootstrap 

Recommended Backend-End technologies:
* .Net Core (any version newer than 5.0, do not confuse it with .Net Framework)
* Node.js with express.js framework

Recommended Databases:
* PostgreSQL (Relational/SQL)
* MongoDB (object oriented)

Recommended Security:
* A native JWT implmentation in whichever backend technology you choose, implemented as a middleware on all the APIs
* AWS Congnito as a service

A side note about databases and financial systems: This is a bank application in which security, data consistency, and precision are high priorities. In this case, a relational database (SQL) is highly recommended.
```

## Dependencies
None

## Acceptance Criteria
* As a team we have access to the Architectural Design Document
* The architectural design document includes an overview of the system's components, such as front-end, back-end, and database.
* The document outlines the interaction patterns and communication protocols between the different components.
* The architectural design document defines the security measures and protocols to ensure data protection and access control.

Aditionally remember that all user stories must also comply the [General Acceptance Criteria](../generalAcceptanceCriteria.md)

## Definition of Done
The following conditions must be meet to consider this user story as done:
* The architectural design document has been reviewed and approved by the development team and stakeholders.
* It is easily accessible to all project team members and stored in a designated location for future reference.
* The architectural design document is aligned with the project's non-functional requirements and overall goals.

---
[Back to Epic](GEP-01-Release-Zero.md) <br>
[Back to Index](../../README.md)
