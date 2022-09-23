# Currency exchange rate calculator
## How to build this app:

Data is retrieved from  another website.
Exchange rate URL returns the data in JSON-format.
UI displays retrieved exchange rate and input field for user to enter amount in Euros.
There is a button to execute the conversion, and result is displayed in output field.

## Get started
- The usual, create-react-app namename
- implement a constant URL that refers to the site where data is retrieved.
- declare other required variables for the application

## Implement UI
- input field to ask for amount (eur)
- output for current rate (gpb)
- button for execution
- output for result

## Implement converting function
Convert-function retrieves the exchange rate and uses that rate to perform conversion.
Function will be run in 'async': application waits for response before continuing.
- use "try" and "await":
application is waiting for response from HTTPS
- "if" and "await"
- "else": if error occures
- "catch"