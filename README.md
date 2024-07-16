# RUN AND INSTALLATION:

### Importing Postman Collection in CI/CD
Json - Postman COLLECTION
[JSON FORMAT FOR IMPORTING](https://github.com/Peter-QA-testing-Journey/INTEGRATION-MANAGEMENT-SYSTEM-FOR-WASTE-IN-CITY/blob/48b2c9dde80e70ddfdd3cf22103a5dfb991317cf/WASTE%20MANAGEMENT%20API.postman_collection.json)

Install Newman (Postman's CLI):
npm install -g newman

### Run the Postman collection:
newman run GIVEN--postman-collection.json

### Json - Mock Fake Data - list of containers for Json SERVER
[lIST OF MOCK DATA FOR JSON SERVER](https://github.com/Peter-QA-testing-Journey/INTEGRATION-MANAGEMENT-SYSTEM-FOR-WASTE-IN-CITY/blob/48b2c9dde80e70ddfdd3cf22103a5dfb991317cf/FICTIONAL_LIST_OF_CONTAINERS.json)


# Project Overview

  
This project demonstrates simulation of development and testing of WASTE MANAGEMENT SYSTEM FOR CITY. 
The focus is on Creating User stories, Tasks, in general Agile "evolution".
Inside this "Agile World" I have focused on CHOSEN USER STORY - LOCATION OF CONTAINERS 
and the TASK TEST CASE with
API testing using Postman and JSON server mock data.

[VISUAL CONCEPT AND RELATIONS](https://github.com/Peter-QA-testing-Journey/POSTMAN-API--PRACTICE--INTEGRATION-SYSTEM-FOR-WASTE-IN-CITY/blob/main/AGILE%20SCRUMDESK%20SCREENSHOTS/Integration%20management%20system%20for%20city%20waste%20department.png)

## The project includes:

### User Stories in ScrumDesk
- Specific requirements and features needed for the system: 
  - [SCRUMDESK - STORY MAP](https://github.com/Peter-QA-testing-Journey/POSTMAN-API--PRACTICE--INTEGRATION-SYSTEM-FOR-WASTE-IN-CITY/blob/main/AGILE%20SCRUMDESK%20SCREENSHOTS/MY%20USER%20STORIES.png)

- Chosen specific USER STORY:
  - [SCRUMDESK - CHOSEN USER STORY in DETAILED](https://github.com/Peter-QA-testing-Journey/POSTMAN-API--PRACTICE--INTEGRATION-SYSTEM-FOR-WASTE-IN-CITY/blob/main/AGILE%20SCRUMDESK%20SCREENSHOTS/USER%20STORY%20-%20LOCATION%20OF%20CONTAINERS.png)

### Task - TEST CASE in 'Done' Section - KANBAN BOARD (TO-DO / IN PROGRESS / DONE)
- Completed task related to TEST CASE for API testing regarding the user story, including HTTP requests and simple tests.
  - [KANBAN BOARD OF TASKS](https://github.com/Peter-QA-testing-Journey/POSTMAN-API--PRACTICE--INTEGRATION-SYSTEM-FOR-WASTE-IN-CITY/blob/main/AGILE%20SCRUMDESK%20SCREENSHOTS/KANBAN%20BOARD%20AND%20TEST%20API%20IN%20DONE.png)

### Test Case
- Detailed test case validating the functionality of the system for this specific user story.
- API for Location of Containers has been tested here:
  - [TEST CASE VIEW](https://github.com/Peter-QA-testing-Journey/POSTMAN-API--PRACTICE--INTEGRATION-SYSTEM-FOR-WASTE-IN-CITY/blob/main/TEST_CASE_AND_BUG_REPORT_DOCUMENTATION/TEST%20CASE%20API.png)

### Bug Report
- Documentation of a discovered bug and its impact on the system.
- Bug has been found here - during the testing of API for Location of Containers.
  - [BUG REPORT VIEW](https://github.com/Peter-QA-testing-Journey/POSTMAN-API--PRACTICE--INTEGRATION-SYSTEM-FOR-WASTE-IN-CITY/blob/main/TEST_CASE_AND_BUG_REPORT_DOCUMENTATION/BUG%20REPORT.png) 

### INSIDE THE POSTMAN ENVIRONMENT - FAKE (MOCK SERVER - JSON SERVER) API Testing


### Json - Postman COLLECTION
- [JSON FORMAT FOR IMPORTING](https://github.com/Peter-QA-testing-Journey/INTEGRATION-MANAGEMENT-SYSTEM-FOR-WASTE-IN-CITY/blob/48b2c9dde80e70ddfdd3cf22103a5dfb991317cf/WASTE%20MANAGEMENT%20API.postman_collection.json)

### Json - Mock Fake Data - list of containers for Json SERVER
- [lIST OF MOCK DATA FOR JSON SERVER](https://github.com/Peter-QA-testing-Journey/INTEGRATION-MANAGEMENT-SYSTEM-FOR-WASTE-IN-CITY/blob/48b2c9dde80e70ddfdd3cf22103a5dfb991317cf/FICTIONAL_LIST_OF_CONTAINERS.json)

### RUN RESULTS DIRECTLY IN POSTMAN
- [RUN RESULTS](https://github.com/Peter-QA-testing-Journey/INTEGRATION-MANAGEMENT-SYSTEM-FOR-WASTE-IN-CITY/blob/48b2c9dde80e70ddfdd3cf22103a5dfb991317cf/RUN%20RESULTS%20IN%20POSTMAN.png)

### RUN RESULTS THROUGH NEWMAN TOOL IN COMMAND LINE
- [RUN RESULTS](https://github.com/Peter-QA-testing-Journey/INTEGRATION-MANAGEMENT-SYSTEM-FOR-WASTE-IN-CITY/blob/main/RUNNING%20COLLECTION%20THROUGH%20NEWMAN%20IN%20CMD.png)

Using Postman for sending HTTP requests (GET, POST, PUT, DELETE) ON FICTIONAL SERVER.

#### RestFul API METHODS:

- **GET (GETTING LIST OF ALL CONTAINERS)**
  - [GET All Containers](https://github.com/Peter-QA-testing-Journey/INTEGRATION-MANAGEMENT-SYSTEM-FOR-WASTE-IN-CITY/blob/01ab872a4665a446efbd7a84da8af4e4666c1de5/get%20request%20all%20containers.png)
  - [GET All Containers PM.TEST](https://github.com/Peter-QA-testing-Journey/INTEGRATION-MANAGEMENT-SYSTEM-FOR-WASTE-IN-CITY/blob/01ab872a4665a446efbd7a84da8af4e4666c1de5/get%20request%20all%20containers%20-tests.png)

- **GET (GETTING LIST OF EMPTIED CONTAINERS)**
  - [GET Emptied Containers](https://github.com/Peter-QA-testing-Journey/INTEGRATION-MANAGEMENT-SYSTEM-FOR-WASTE-IN-CITY/blob/01ab872a4665a446efbd7a84da8af4e4666c1de5/get%20emptied%20containers.png)
  - [GET Emptied Containers PM.TEST](https://github.com/Peter-QA-testing-Journey/INTEGRATION-MANAGEMENT-SYSTEM-FOR-WASTE-IN-CITY/blob/01ab872a4665a446efbd7a84da8af4e4666c1de5/get%20emptied%20requests%20-%20tests.png)

- **GET (GETTING LIST OF UNEMPTIED CONTAINERS)**
  - [GET Unemptied Containers](https://github.com/Peter-QA-testing-Journey/INTEGRATION-MANAGEMENT-SYSTEM-FOR-WASTE-IN-CITY/blob/01ab872a4665a446efbd7a84da8af4e4666c1de5/GET%20unemptied%20containers%20-%20not%20found.png)
  - [GET Unemptied Containers PM.TEST](https://github.com/Peter-QA-testing-Journey/INTEGRATION-MANAGEMENT-SYSTEM-FOR-WASTE-IN-CITY/blob/48b2c9dde80e70ddfdd3cf22103a5dfb991317cf/GET%20unemptied%20containers%20-%20404%20status%20not%20found.png)

- **POST (CREATING A NEW LOCATION OF CONTAINER)**
  - [POST Create New Container](https://github.com/Peter-QA-testing-Journey/INTEGRATION-MANAGEMENT-SYSTEM-FOR-WASTE-IN-CITY/blob/48b2c9dde80e70ddfdd3cf22103a5dfb991317cf/POST%20request%20-%20creating%20new%20location.png)
  - [POST Create New Container PM.TEST](https://github.com/Peter-QA-testing-Journey/INTEGRATION-MANAGEMENT-SYSTEM-FOR-WASTE-IN-CITY/blob/48b2c9dde80e70ddfdd3cf22103a5dfb991317cf/POST%20-%20creating%20new%20container-location%20-%20test.png)

- **PUT (UPDATE EXISTING LOCATION OF CONTAINER)**
  - [PUT Update Container](https://github.com/Peter-QA-testing-Journey/INTEGRATION-MANAGEMENT-SYSTEM-FOR-WASTE-IN-CITY/blob/48b2c9dde80e70ddfdd3cf22103a5dfb991317cf/PUT-%20updating%20existing%20container%20id%204-status%20on%20emptied.png)
  - [PUT Update Container PM.TEST](https://github.com/Peter-QA-testing-Journey/INTEGRATION-MANAGEMENT-SYSTEM-FOR-WASTE-IN-CITY/blob/48b2c9dde80e70ddfdd3cf22103a5dfb991317cf/PUT%20-%20updating%20existing%20container%20on%20status%20emptied%20-%20test.png)

- **DELETE (ERASING OF EXISTING LOCATION OF CONTAINER)**
  - [DELETE Container](https://github.com/Peter-QA-testing-Journey/INTEGRATION-MANAGEMENT-SYSTEM-FOR-WASTE-IN-CITY/blob/48b2c9dde80e70ddfdd3cf22103a5dfb991317cf/DELETE%20-%20erasing%20existing%20container%20with%20id%205.png)
  - [DELETE Container PM.TEST](https://github.com/Peter-QA-testing-Journey/INTEGRATION-MANAGEMENT-SYSTEM-FOR-WASTE-IN-CITY/blob/48b2c9dde80e70ddfdd3cf22103a5dfb991317cf/DELETE%20-erasing%20an%20existing%20container%205%20-%20test.png)


## Project Goals
- Demonstrating the API testing and Agile process with tool SCRUMDESK.
- Effectively monitor the waste management situation.
- Establish an efficient monitoring mechanism for the waste situation from the perspective of Waste  Department employees and Citizens.

