# API-Testing-Project-JSONPlaceholder
A manual API testing project performed on JSONPlaceholder REST APIs using Postman, covering GET, POST, PUT, and DELETE operations with complete documentation.
API Testing Project – JSONPlaceholder

Project Overview:
This project demonstrates manual API testing using JSONPlaceholder, a public fake API service for practice and learning.

Note: Real websites cannot be tested directly due to security, privacy, and access restrictions. JSONPlaceholder provides a safe environment to practice API testing without affecting real systems.

Objective:
Validate API endpoints (GET, POST, PUT, DELETE) for correctness, response status, body content, and behavior under different scenarios.
Develop structured test artifacts including test plan, test cases, scenarios, and execution reports.


Tools Used:
Postman – to execute API requests
Excel / CSV – to document test cases, scenarios, and execution reports
JSONPlaceholder – for simulated API endpoints


Tested API Endpoints
Method	Endpoint	Description
GET  	/users	Fetch all users
GET  	/users/1	Fetch a single user by valid ID
GET 	/users/999	Verify invalid user ID returns 404
POST	/posts	Create new post (valid & missing fields)
PUT 	/posts/1	Update existing post (valid & empty data)
DELETE	/posts/1	Delete post (valid, invalid, already deleted)

How to Run the Tests
Open Postman.
Import requests manually using TestCases.csv endpoints.
Execute requests following the test steps in each test case.
Verify response status, response body, and match against expected results.
Document actual results in TestExecutionReport.csv.


Key Artifacts
Document	Purpose
TestPlan.csv	Defines objectives, scope, and approach
TestCases.csv	Test cases including TC ID, endpoint, method, expected status, and body
TestScenarios.csv	Derived scenarios for all API operations
TestExecutionReport.csv	Pass/Fail results for each test case
Screenshots/	Evidence of executed API requests


Conclusion
This project highlights knowledge of structured API testing using a safe practice environment. All test cases are well-documented, executed, and mapped to scenarios, demonstrating strong QA methodology and understanding of API testing principles.
