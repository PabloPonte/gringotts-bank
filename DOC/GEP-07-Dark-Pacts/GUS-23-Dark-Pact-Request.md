# GUS-23 Operation: Dark Pact Request
_Loan Simulation and Request_

## Definition
As an Overseer or Minion User, I need a page to perform the Dark Pact Request operation.

## Details

The Dark Pact Request consist in two steps: Loan Simulation and Loan Request.

During the simulation, first of all a Mage is selected. After that, a Loan Type is selected from a list. Immediately after the loan type selection, the application must validate if the selected mage fulfills the requirements for that loan type. If the mage doesn't meet the criteria, a clear message must be displayed, and the application must prevent further progress in the operation.

With the mage and the loan type selected, the following information must be shown under the "Loan Type Details" section:
* Loan Type
* APR
* Instalments Range
* Amount Range
* Origination Fee

A section titled "Loan Request" must show a form with the following inputs:
* Loan Amount
* Instalments
* Request Date
* A "Simulate" button that will run the loan simulation.

A section titled "Loan Details" must show a summary subsection indicating the instalments quantity, total amount to pay, and the first and last instalment due dates. A second subsection with a table containing the following information for each instalment: instalment number, due date, principal amount, interest amount, and other charges.

At the end of the details section, a "Request" button must perform the formal request of the loan. A "Cancel" button must redirect to the main page.

All the limitations defined on the loan type must be validaded on the simulation and the request.

### Loan Conformation

The loan is composed of instalments, the quantity of which is defined by user input. Each instalment has an ordinal number, a due date, a principal amount, an interest amount, and other charges that can apply, such as the origination fee.

The instalment number is sequential, beginning at 1 and ending at the total instalment quantity.

All the instalments have a due date corresponding to the 20th day of the month, one month after the previous instalment's due date. The first instalment's due date is the 20th day of the next month following one month from the request date. For example, a loan requested on 15/03 will have the first instalment's due date on 20/04, the second on 20/05, and so on.

All the instalments have the same amount of principal. To calculate this amount, simply divide the total loan amount by the number of instalments.

All the instalments have the same amount of interest. To calculate this amount, simply divide the total interest amount by the number of instalments.

To calculate the total interest amount, use the following formula:

 $$ TotalInterest = LoanAmount \times \frac{APR}{100} \times \frac{InstallmentsNumber}{12}$$

For example, a loan of Sk$100,000 with a 45.00% APR and 18 instalments has a total interest of Sk$67,500. Each instalment consists of Sk$5,555.56 as principal and Sk$3,750 as interest.

### Formal Request

Upon pressing the "Request" button, a confirmation dialog must be displayed, if confirmed the loan must be saved in a "Pending" state.

---
---
##

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
