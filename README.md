Example 1: Automation to execute the API endpoints outlined in https://jsonplaceholder.typicode.com/ 
Requirement:
All the resources and routes have at least one test case. 
Each test case only executes one endpoint.
All resources and routes are tested
Write some tests for each endpoint such that the endpoint is supposed to fail with a non-200 status code, and validate the expected status code returned.

Basic Framework structure (request generation and validation):
For the test cases above, modularize the code so that there are functions to:

1. Generate the endpoint.
2. Generate the HTTP request.
3. Generate any headers.
4. Generate any data
5. Make the HTTP request
6. Parse out the response status code and body

For validation:
Validate the expected status code is the actual status code
Validate that expected data is somewhere in the response body
In the event of errors and test failures, ensure that the tests have failed. 






Example 2: Visit the Star Wars API https://swapi.dev/ and the documentation https://swapi.dev/documentation

Expectation : 

Create a framework with the tools and technologies of your choice.
Each validation is to be performed as a separate test.
At the end of the test execution, the framework should generate a report with the number of tests and their corresponding execution status.
Perform the following validations:

Verify that the “people” endpoint is returning a successful response.
Verify that the total number of people where height is greater than 200 matches the expected count (10 at the time this was assigned).
Verify that the ten individuals returned are:
Darth Vader. Chewbacca, Roos Tarpals, Rugor Nass, Yarael Poof, Lama Su, Tuan Wu, Grievous, Tarfful, Tion Medon
Verify that the total number of people checked equals the expected count (82 at the time)