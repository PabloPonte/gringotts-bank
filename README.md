# Gringotts - Template Project - v0.6.0

_A simple bank application project template_

Gringotts is a Template Project that contains all business and functional definitions needed to develop a full application. It contains no technical definitions nor restrictions, but a few requisites. You can use any technology and language that you like.

You should start reading the [Project Brief](DOC/brief.md), that contains a simplified explanation and scope of the project.

The project has a guideline in form of [Epics](DOC/epics.md) and [Releases](DOC/releases.md) that you must respect and complete in certain order (mostly due dependencies).

```
Suggestions:
============ 
    
This is a suggestion box, at some points in this project, you will need to make a choice or decision. 
On some of those cases, the proyect will make a suggestion, giving some options and recomendations on boxes like this one.

```

## How to start?
As stated before, it is recommended to start by reading the [Project Brief](DOC/brief.md), then the [Epics List](DOC/epics.md), and [Release Plan](DOC/releases.md) to have a general understanding of the scope of the project.

After that, you can read the entire definition (all epics and all user stories), but it's not really necessary. Instead, it is recommended to read at least all the user stories needed for the first release (all the epics for the MVP).

You can download or fork this repository and work directly here, although it's recommended to transfer all these definitions to a project management tool.

## Considerations

This project is **intended as an exercise**. It can contain errors, lack of definitions, misconceptions, and inconsistencies. This is done this way by design to test and teach a team how to deal with these kinds of situations.

This proyect was designed to train a full development team, including Software Engineers and Quality Engineers. It contains specific definitions to challenge the team in the technical implementation, solution design, infraestructure and deployment, quality assurance, and team and proyect management, it requires a person that fullfills the role of Product Owner or final client (let's assume the bank's owner), that fills the intented gaps of definitions and takes some management tasks.

You can use it in a way that fills your needs, ignoring some specific requirements or going deeper in some topics. For example you can decide to do only the database and backend, ignore the testing and quality requirements, do a more complex documentation, or skip the deployment and run the entire solution locally.

The proyect was used for the first time on a coding bootcamp, with a team of trainees/junior developers and testers with a full dedication commitment (8 daily hours), and resolved the first 6 epics in about 10 weeks.

## General Epic and User Stories Index
* [GEP-01 Release Zero](/DOC/GEP-01-Release-Zero/GEP-01-Release-Zero.md)
    * [GUS-01 Architectural Design](/DOC/GEP-01-Release-Zero/GUS-01-Architectural-Design.md)
    * [GUS-02 Environments Definition](/DOC/GEP-01-Release-Zero/GUS-02-Environments-Definition.md)
    * [GUS-03 Repositories Definition](/DOC/GEP-01-Release-Zero/GUS-03-Repositories-Definition.md)
    * [GUS-04 Methodology and Management](/DOC/GEP-01-Release-Zero/GUS-04-Methodology-Management.md)
    * [GUS-05 Splash Page](/DOC/GEP-01-Release-Zero/GUS-05-Splash-Page.md)
    * [GUS-06 Healtcheck API](/DOC/GEP-01-Release-Zero/GUS-06-Health-API.md)
    * [GUS-07 Database Access](/DOC/GEP-01-Release-Zero/GUS-07-Database-Access.md)
* [GEP-02 Security](/DOC/GEP-02-Security/GEP-02-Security.md)
    * [GUS-08 Users Definition](/DOC/GEP-02-Security/GUS-08-Users-Definition.md)
    * [GUS-09 Authenticaion API](/DOC/GEP-02-Security/GUS-09-Authentication-API.md)
    * [GUS-10 Login Page](/DOC/GEP-02-Security/GUS-10-Login-Page.md)
    * [GUS-11 Main Page](/DOC/GEP-02-Security/GUS-11-Main-Page.md)
* [GEP-03 Mages](/DOC/GEP-03-Mages/GEP-03-Mages.md)
    * [GUS-12 New Mage](/DOC/GEP-03-Mages/GUS-12-New-Mage.md)
    * [GUS-13 Mages List](/DOC/GEP-03-Mages/GUS-13-Mages-List.md)
    * [GUS-14 Modify Mage](/DOC/GEP-03-Mages/GUS-14-Modify-Mage.md)
    * [GUS-15 Mages Migration](/DOC/GEP-03-Mages/GUS-15-Mages-Migration.md)
* [GEP-04 Accounts](/DOC/GEP-04-Accounts/GEP-04-Accounts.md)
    * [GUS-16 Account Balance](/DOC/GEP-04-Accounts/GUS-16-Account-Balance.md)
    * [GUS-17 Transactions History](/DOC/GEP-04-Accounts/GUS-17-Transactions-History.md)
    * [GUS-18 Account Operations](/DOC/GEP-04-Accounts/GUS-18-Account-Operations.md)
* [GEP-05 Arcane Transmissions](/DOC/GEP-05-Arcane-Transmissions/GEP-05-Arcane-Transmissions.md)
    * [GUS-19 Operation Arcane Transmissions](/DOC/GEP-05-Arcane-Transmissions/GUS-19-Operation-Arcane-Transmissions.md)
* [GEP-06 Mystical Insights](/DOC/GEP-06-Mystical-Insights/GEP-06-Mystical-Insights.md)
    * [GUS-20 Overseer Dashboard](/DOC/GEP-06-Mystical-Insights/GUS-20-Overseer-Dashboard.md)
    * [GUS-21 Account Balance Histogram](/DOC/GEP-06-Mystical-Insights/GUS-21-Account-Balance-Histogram.md)