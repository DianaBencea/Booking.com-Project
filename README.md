  The scope of the final project
  ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application.
Application under test: [Booking.com](https://www.booking.com/index.ro.html?label=gen173nr-1BCAEoggI46AdIM1gEaMABiAEBmAEguAEXyAEM2AEB6AEBiAIBqAIDuALFqqmuBsACAdICJGI0YjZhZmFiLTYwMDUtNDNmZS04OGVmLTFhYmVjZjgxYTVkY9gCBeACAQ&sid=c1f4c3512d19e2a53e85850b4937f62a&keep_landing=1&sb_price_type=total&)

  API Documentation:

  Tools used: Jira , zephyr

  Functional specifications :[JIRA  Projects-Diana_Bencea_TMTA18-DBT board/ Booking](https://itfclasses.atlassian.net/jira/software/c/projects/DBT/boards/302?issueParent=15181)

Functionalities in scope :
 1. Booking official site acces
 2. Booking functionality Stays module


Functionalities not in scope :
 1. Business process
 2. Customization or configuration
    
1.1

Test planning
The Test Plan is designed to describe all details of testing for the functionality of Booking.com application. The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan.

1.1.1 Roles assigned to the project and persons allocated
Project manager - Ionescu Cristian
Product owner - Ene Mihai
Software developer- Popescu Robert
QA Engineer - Bencea Diana

1.1.2 Entry criteria
Entry criteria for software testing must be clearly defined to ensure a smooth and effective testing process. Before testing can begin, the following conditions must be met:

Availability of the required software builds and versions.
Completion of test enviorment setup and configuration
Preparation and documentation of test cases, ensuring coverage of all relevant scenarios
Confirmation of readliness from stakeholders or project management
Entry criteria: smoke test passed (being the most basic type of test, this is a very important entry criteria in the process of testing) testing environment is up and running

1.1.3

Exit criteria
Test coverage goals have been achieved, ensuring that all critical functionalities and use cases have been tested
All acceptance criteria outlined in the project requirements or user stories have been satisfied
All high-priority defects have been resolved
Exit criteria: 92% of tests are passed no Critical issues have Open status update tests are 100% passed (update tests will not generate other new issues that impact the application)

1.1.4 Test scope
Tests in scope:
Booking login and Stays module to function at its max capacity without any error ocurred
Regression testing
Early testing

Tests not in scope:
Automation Testing
Designing the user interface
Fixing bugs


1.1.6 Evaluating entry criteria

The entry criterias defined in the Test Planning phase have been achieved and the test process can continue.

Testing the log in functionality

Verification log in

Test Case 1: Description: Test login successfully

Preliminary conditions: The user must be on the log in page

Execution steps:

Enter valid user
Enter valid password
Press the log in button
Test data: user valid / password valid / Current results: log in succsefully Expected results: The user must be redirected to the home page

1.2 Test Monitoring and Control

1.3 Test Analysis

The testing process will be executed based on the above requirements for the Dependents module. The following test conditions were found:

Enter test conditions here

1.4 Test Design
The test cases with steps can be viewed here: [test_cases.pdf](https://objects.githubusercontent.com/github-production-repository-file-5c1aeb/744105153/14165184?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20240219%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240219T141643Z&X-Amz-Expires=300&X-Amz-Signature=cc1e65d4dc1a65dbdc7f2ce962d5c99e3526290c73fd67a1a6008a4438a24cf5&X-Amz-SignedHeaders=host&actor_id=151565785&key_id=0&repo_id=744105153&response-content-disposition=attachment%3Bfilename%3Dtest_cases.pdf&response-content-type=application%2Fpdf)
Functional test cases were created in Zephyr Squad based on the analysis of the specificationS
The test cases with steps can be viewed here
1.5 Test Implementation

1.6 Test Execution
Test cases are executed on the created test Cycle summary: cycle_summary.pdf
The complete bug reports can be found here: work-shift.bug.pdf
Work shifts -> bug
The following elements are needed to be ready before the test execution phase begins.
here what needs to be ready for the test execution to begin:
Ensure that the test enviorment is set up, test data is prepared and all necessary test resources, including test script and tools are in place.
Verify that the system under test is stable and ready for testing.

1.7 Test Completion Exit criteria was evaluated and passed
The traceability matrix was generated and can be found here: [Traceability Report (Direct Only) (Jira).pdf](https://github.com/DianaBencea/Manual_Testing_Project_For_-Booking.com-.md/files/14334843/Traceability.Report.Direct.Only.Jira.pdf)

Tests execution report:
DBT-46	Filter by Review Score- PASS
DBT-45	Filter by Meals- PASS
DBT-44	 Filter Property by facilities - PASS
DBT-43	Filter by property type- PASS
DBT-41	Reserve for more than 10 rooms- FAIL
DBT-40	Reserve for more than 10 children- FAIL
DBT-38	Reserve for more than 30 perso - FAIL
DBT-36	Date check-out  smaler then date check in -FAIL
DBT-35	Open Stays module- PASS
DBT-34	Functionality of icon from the first pag - PASS
DBT-30	Login button - PASS
 




