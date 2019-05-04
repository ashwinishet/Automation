# Automation
---------------------------------------------------------------------
Automation Testing of Gurukula Application
--------------------------------------------------------------------

Automation Framework : 
The Automation framework has been built with Selenium, Java and TestNG. Required libraries are added as external jar files.
* The Page Object Model has been employed to build the test framework.
* Various pages and interaction with their elements have been specified in the main.pom package. 
* The tests are built into a separate package main.test
* Data to be given input is stored in Data.properties file inside main.resources package
* Some of the reusable code is being placed inside CommonCode.java in main.utility package

Automated Tests : 
1. Registering a new user
2. Logging in the application and logging out
3. Viewing and Editing logged in information settings page
4. Password Edit scenario
5. Adding/Searching/Viewing/Editing/Deleting a branch
6. Adding/Searching/Viewing/Editing/Deleting a staff

Steps to Run :
1. Run the testng.xml file as a TestNG suite 

Output : 
1. Automation logs are recorded in the GurukulTestLogs.out as and when the test steps are performed
2. For failed test cases, screenshots are captured inside the Screenshots Folder with test name as name of the screenshot

Things which can be added for further enhancements of the framework :
Project dependencies may be added to Maven pom.xml
More negative scenarios can be added for each of the inputs in different pages
Session page is not covered, as I did not see any major functionality, other than deleting the session information
Adding many records for Branch/ Staff to test Pagination
