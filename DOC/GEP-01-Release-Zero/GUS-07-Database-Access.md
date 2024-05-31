# GUS-07 Database Access 
_Database access_

## Definition
As a development team, we need database credentials, to perform a test connection to the database to check that the database is correctly deployed.

## Details

A database connection to an empty database is needed, just to check the avaliabilty.

The credentials provided must have only the necessary permissions for the application development.

## Dependencies
Database technology defined on [Architectural Desing](GUS-01-Architectural-Design.md) need to be defined in order to develop this API.

Infraestructure defined on [Environments Definition](GUS-02-Environments-Definition.md) need to be defined in order to deploy this API.

## Acceptance Criteria
* As any person connected to the internet I have access to this database with the given credentials.
* The credentials provided must have only development permissions on a given schema, not an admin user.

Aditionally remember that all user stories must also comply the [General Acceptance Criteria](../generalAcceptanceCriteria.md)

## Definition of Done
The following conditions must be meet to consider this user story as done:
* The Database is online and accesible from anywhere with the given credentials.
* The Database exists for all the defined environments.
* All members from the develpment team have the credentials to connect to the database.

---
[Back to Epic](GEP-01-Release-Zero.md) <br>
[Back to Index](../../README.md)