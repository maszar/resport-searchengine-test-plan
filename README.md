# resport-searchengine-test-plan
Example of the test plan

Test Plan of the resport.eu search engine

1. Introduction
The main purpose of testing activities is to provide customers with information about the quality of the tested product.
The prepared document contains key information on the testing activities. All software components that will be verified and the type of tests that will be carried out are listed.

2. Scope of tests
- Executed types of tests:
 - functional
 - performance

- Types of tests that will not be performed:
 - automatic tests - insufficient budget
 
3. Test items
The component being tested is the search engine from the resport.eu home page, taking into account the entire logic of filtering through the appropriate fields.

4. Pass/fail criteria
 - execution of designed test cases
 - server response time does not exceed 700ms
 
5. Entry/exit criteria
- 5.1. Entry Criteria:
 - search engine implementation phase completed
 - working and configured test environment
 - access to a running and configured virtual machine
- 5.2. Exit Criteria:
 - all cases have been successfully completed
 - the component meets all the established assumptions from the attached documentation
 
6. List of functional requirements to be tested
Attaching all documentation, user stories, scenarios, etc.

7. Test environment:
 - test server (Development)
 - Windows 10 Pro 64 bit
 - browsers participating in the tests: Firefox, Chrome, Edge, Opera, Safari
 
8. Test schedule
- 8.1. Carrying out functional tests:
 - functionality verification based on user story - 5h
 - execution of previously designed test cases - 2h
 - verification of the backend layer - 2h
- 8.2. Performing performance tests:
 - verification of the average response time - 0,5h
 - verification of the maximum number of requests at which the search engine works stably - 0,5h.
 
9. Test Report:
 - list of completed test cases with statuses
 - measurements from performance tests
 - other test reports
 
10. Tool List:
 - Jmeter
 - TestLink
 - Jira
 - BrowserStack
 
11. Incident and error management
In the testing process, each detected error should be properly reported to the Jira system.
Taking into account the error priority, the assigned person (developer), the affected component.
According to the adopted flow, such a problem should be fixed by the developer and sent to retests.

12. Roles and Responsibilities
- Marzena Chaczko, R.S. - preparation of test cases
- Marzena Chaczko - execution of test cases
- R.S. - user story verification









