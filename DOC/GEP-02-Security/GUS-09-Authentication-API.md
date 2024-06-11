# GUS-09 Authentication API
_Authentication API endpoints_

## Definition
As a development team, we need an authentication API to validate the user and authorize the access to all the features of the application.

## Details

Just the authentication API is needed, the API endpoint is expected as result.

If the login is successfull, the response must indicate user name, profile picture and user role/type.

## Dependencies
The security implementation defined on [Architectural Design](../GEP-01-Release-Zero/GUS-01-Architectural-Design.md) need to be defined.

## Acceptance Criteria
* The authentication API endpoint is publicly available.
* On successfull login, the user name, login picture URL and user role are present on the response.
* On failed login, the message "invalid credentials" is returned.
* The response HTTP codes are consistent with the resutls.
* All the configured users can login successfully using this API with the correct credentials.

Aditionally remember that all user stories must also comply the [General Acceptance Criteria](../generalAcceptanceCriteria.md)

## Definition of Done
The following conditions must be meet to consider this user story as done:
* The API endpoint is deployed.

---
[Back to Epic](GEP-02-Security.md) <br>
[Back to Index](../../README.md)
