# GUS-15 Mages Migration
_Migration of mages data from a previous system_

## Definition
As an Application User, I need the mages data from a previous application migrated into Gringotts in order to reuse my clients database.

## Details
A [CSV Dump File](mages_dump.csv) containing the data from the previous application is provided.

All migrated data must follow the same validations as the new mages.

As a result a report is expected containing the following info:
* Number of Mages successfully migrated for each house
* Number of Mages non-migrated for each cause/reason

## Dependencies
* The [New Mage](GUS-12-New-Mage.md) feature must be completed.

## Acceptance Criteria
* As an authenticated user, I can see all the successfully migrated mages in the application.
* A report with the migration results is provided after the migration.
* All the successfully migrated mages have consistent and validated data.
* All unsuccessful cases have an acceptable explanation.
* The dump file is fully processed.

Aditionally remember that all user stories must also comply the [General Acceptance Criteria](../generalAcceptanceCriteria.md)

## Definition of Done
The following conditions must be met to consider this user story as done:
* The dump file is fully processed.
* All the non-migrated data has the cause accepted.
* All the migrated data is validated and fully accessible on the application.

---
[Back to Epic](GEP-03-Mages.md) <br>
[Back to Index](../../README.md)
