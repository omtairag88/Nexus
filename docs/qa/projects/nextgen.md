# NextGen Project 

This is a temporery site for NextGen ERP QA and Test reletaed topcis. 

## Links 
<href>

https://eqn-nextgen.atlassian.net/jira/software/c/projects/NGE/boards/71
https://equinor.qtestnet.com/p/120469/portal/project#id=5266323&object=4&tab=testexecution

Main contact person: Mattis Eine Furuset

## Test Strategy: 

<center>
<iframe src="https://statoilsrm.sharepoint.com/sites/IntegratedNextGenERPTeam/_layouts/15/Doc.aspx?sourcedoc={6a3c5af4-97bb-44da-bb28-d89f2ae27629}&amp;action=embedview&amp;wdAr=1.7777777777777777" width="952px" height="564px" frameborder="0">Dette er et innebygd <a target="_blank" href="https://office.com">Microsoft Office</a>-dokument. Leveres av <a target="_blank" href="https://office.com/webapps">Office</a>.</iframe>
</center>

## Test Phases

|   |Unit Testing (UT)|Functional Testing (FT)|System Integration Testing (SIT)|User Acceptance Testing (UAT)|
|---|---|---|---|---|
| **Testing Phase**  | Development  | Development  | Release  | Release  |
| **System**  | D09 (Client 390)  | Q09 (client 590)  | Q09 (client 490)  | T09 (client 590)  |
| **Test Methods**  | Automated code testing (TDD with ABAP Unit) <br>code review  | Automated regression testing;<br>Exploratory testing <br>Functional Testing  | Non-functional Testing (performance, usability, reliability, authorization, et)<br>Functional Testing  | Non-functional Testing (performance, usability, reliability, authorization, et)<br>Functional Testing  |
| **Ways of testing**  | -  | -  | Bottom-up  | Beta testing  |
| **Definition of "Done"**  | list of criteria that ensures the functional need is covered<br>Technical DoD  | PO or SME test approval  | SME & Lead users test approval  | End users test approval  |
| **Who** | Developers<br>functional specialists | functional Specialists | Functional Specialists<br>QA SMEs (automated testing)<br>Selected key users (SIT2) | Key Users<br>End users<br>QA SMEs (automated testing) |
| **Expected Automation Level** | 0% | 0%<br>*"in sprint" automated regression testing executed on top of manual tests* | Up to 30% | Up to 50% |
| **Entry Criteria** | Define MVP test approach (Release/EPICs/User Stories) <br> Define Test Strategy & Approach <br> Define Test Automation Strategy <br> Resource planning <br> Setup of Test Suite and Tosca <br> Users Enablement for Test Suite & Tosca <br> Provide test case template and test case naming convention | Same as UT | Provide test plan (testing timeline, test case templates, defect resolution process, defect prioritization, define SLAs, etc.) <br> Test community for IT is confirmed  <br> Ensure test tool access  <br> Prepare tool setup, e.g. tester assignment, test plan creation <br> Conduct tester trainings  <br> Collect and upload test cases (approved by validation team) <br> All required data loaded (Mock 1 completed) <br> Prepare system enablement (e.g. automatic regression testing) <br> Authorisation model ready, roles assigned to SIT2 testers | Provide test plan (testing timeline, test case templates, defect resolution process, defect prioritization, define SLAs, etc.) <br> Test community for UAT is confirmed  <br> Ensure test tool access  <br> Prepare tool setup, e.g. tester assignment, test plan creation <br> Conduct tester trainings  <br> Collect and upload test cases (approved by validation team) <br> All required data loaded (Mock 2 completed) <br> Prepare system enablement (e.g. automatic regression testing) |
| **Exit Criteria** | Ensure that the Business Requirements are implemented for Sprint scope (EPICs/US) – Product Owner sign-offs received <br> Test data required for testing prepared (manual creation) <br> Test scenarios & test cases created <br> Unit tests & functional tests successfully completed <br> Defect management process steps executed <br> Automation priorities agreed <br> Evidence of FT created <br> Exploratory testing documentation delivered <br> End-to-end integration test cases created (if neccessary/possible) | Same as UT | End-to-End Integration test successfully completed with expected completion results (as per Statement of Work) <br> TBD* % of very high defects resolved (focus on critical test cases) for SIT1 & SIT2 respectively <br> Product Owners & Process Area Leads sign-offs received <br> Authorization roles tested (SIT2 only, incl. negative testing) <br> Data validation done <br> Bug fixing phase finalized | User Acceptance Test successfully completed with expected results (as per Statement of Work) <br> No critcal or very high defects remainig <br> Solution Owner, Product Owners & Process Area Leads sign-offs on UAT results received <br> Authorization roles tested (incl. negative testing) <br> Data validation done <br> Finalize the UAT and ticket resolution phase <br> Transfer remaining tickets for hypercare <br> Communicate the UAT completion status for deployment preparation <br> Bug fixing phase finalized |