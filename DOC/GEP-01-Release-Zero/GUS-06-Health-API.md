# GUS-06 Healthcheck API 
_Healthcheck API endpoint_

## Definition
As a development team, we need a healthcheck API endpoint to check that the API layer is correctly deployed.

## Details
The endpoing is just a simple way to check that the API server is up and runing.

No securtiy or authentication mechanism is needed.

The enpoint should expect a GET call and should not expect or interact with any request body, headers nor query string.

The response must be a json with the message "OK" and the HTTP response code 200.

## Dependencies
Backend technology defined on [Architectural Desing](GUS-01-Architectural-Design.md) need to be defined in order to develop this API.

Infraestructure defined on [Environments Definition](GUS-02-Environments-Definition.md) need to be defined in order to deploy this API.

## Acceptance Criteria
* As any person connected to the internet I have access to this APOI endpoint.
* The response code must be 200 and the response body must be a json document with the "OK" message.

Aditionally remember that all user stories must also comply the [General Acceptance Criteria](../generalAcceptanceCriteria.md)

## Definition of Done
The following conditions must be meet to consider this user story as done:
* The API endpoint is online and accesible from anywhere.
* The API endpoint exists for all the defined environments.

---
[Back to Epic](GEP-01-Release-Zero.md) <br>
[Back to Index](../../README.md)