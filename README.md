# Random-User-API-Performance-Test-Jmeter

## Technology and Tools used in this Project
- Jmeter

## Project Scenarios
 - Here Load testing is performed using [Random Data API](https://random-data-api.com/api/v2/users) where the expected load is 120000 for 12 hours. 
   Severall tests has been performed for 60s,300s,600s and 900s load using Jmeter. The tests having TPS breakdown are summarized in excel spreadsheet and the images 
   of tests screenshots are attached in doc file containing HTML report for the last test of 900s having 2500 users.
   
 - And also here stress testing is performed using [Random Data API](https://random-data-api.com/api/v2/users) for finding the bottleneck/stress test point 
   (At which point the system starts to show 1% error) where the expected load is 120000 for 12 hours.Severall tests has been performed for 60s,300s,600s and 900s load using Jmeter. And The users has have been 166, 833, 
   1666, 2500, 3500, 3200 users.  The tests having TPS breakdown are summarized in excel spreadsheet and the images of tests screenshots are attached in doc file 
   containing HTML report for the last test of 900s having 3500 users.

## How to run this project:
 - Clone this project or download the .jmx file in the project directory.

 ## Prerequisite
  - JDK must be installed

