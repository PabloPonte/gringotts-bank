# GUS-22 Dark Pacts Parameters Configuration
_Loans Parameters Configurations_

## Definition
As an Overseer User, I need a page to manage and configure all the different parameters for all the Dark Pacts Operations.

## Details

A Dark Pact is a Loan from the bank to a Mage. A Loan have a "Loan Type", this is a way to group several parameters that determines how each instance of that kind of loan works.

Each Loan Type has the following parameters:
* **Type Name**: A name to identify the loan type.
* **Minimum and Maximun Instalments**: Range of instalments quantity.
* **Minimum and Maximum Loan Amount**: Range of the amount to loan.
* **APR**: stands for Annual Percentage Rate, is the interest percentage that applies per year.
* **Origination Fee**: is the amount to be charged on the loan approval, usually added to the first instalment. Can be expresed as a fixed value or a percentage of the total loan amount. 
* **Age Restriction**: Range of Mage age, to qualify for this type of loan. This values are expresed in years.
* **Minimum Mage Tenerue**: Time since the Mage has been a client, expresed in months.
* **House Restriction**: Indicates if the loan type is only avaliable for mages that belongs to a certain house.
* **Status**: the loan type can be "Active" or "Inactive", this value determines if a new loan can be created using this type.

All the values are expresed on Sickles.


As an Overseer a need a page to do the following actions:
* List all the Loan Types with their parameter values
* Create a new Loan Type (all the parameters are mandatory, except the house restriction)
* Edit an existing Loan Type

### Initial Loan Types

The bank currently have the following loan types:

|Name|Min Instal|Max Instal|Min Amount|Max Amount|APR|Orig Fee|Min Age|Max Age|Min Tenerue|House|
|--|--:|--:|--:|--:|--:|--:|--:|--:|--:|--|
|Muggle Pact|3|12|sk$5,000|Sk$75,000|45.00%|sk$5,000|0|50|6||
|Regular Mage Pact|6|60|sk$50,000|Sk$500,000|35.00%|3.50%|0|99|3||
|Old Clients Pact|6|120|sk$50,000|Sk$1,000,000|30.00%|3.00%|35|200|72||
|Ravenclaw Express Pact|1|6|sk$5,000|Sk$30,000|40.00%|SK$0|0|99|0|Ravenclaw|

## Page Design

There is no specific mockup for this page. Use the same criteria from existing pages.

## Validations
* The Loan Type Name must be unique.
* All the numerical parameters are mandatory and must be postive values or zero.
* The max values for a range must be igual or greater than the min value of that range.
* The house restriction parameter is optional and represents only one existing.
* The loan types cannot be deleted, only deactivated.

## Dependencies
None besides those defined on the Epic.

## Navigation and Security
In the navigation section this feature access must be on the following route:

**Configuration -> Dark Pacts Parameters**

This feature must be only accessible for users with the Overseer Role.

## Acceptance Criteria
* As an Overseer user, I have access to this page from the navigation bar.
* As an Overseer user, I can list all the existing loan types.
* As an Overseer user, I can create a new loan type.
* As an Overseer user, I can modify an existing loan type.
* All the defined validations are implemented.

Additionally remember that all user stories must also comply the [General Acceptance Criteria](../generalAcceptanceCriteria.md)

## Definition of Done
The following conditions must be met to consider this user story as done:
* The Dark Pacts Configuration page is deployed in all layers.
* The Loan Types defined on this User Story are correctly configurated.
* All the validations are properly implemented.

---
[Back to Epic](GEP-07-Dark-Pacts.md) <br>
[Back to Index](../../README.md)
