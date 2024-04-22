Automation to execute the API endpoints outlined in https://jsonplaceholder.typicode.com/ 
Requirement:
All the resources and routes have at least one test case. 
Each test case only executes one endpoint.
All resources and routes are tested


Basic Framework structure (request generation and validation):
For the test cases above, modularize the code so that there are functions to:

Generate the endpoint
Generate the HTTP request
Generate any headers
Generate any data
Make the HTTP request
Parse out the response status code and body
For validation:

Before validation, please ensure each test case contains a code block

Validate the expected status code is the actual status code
Validate that expected data is somewhere in the response body
In the event of errors and test failures, ensure that the tests have failed. 
