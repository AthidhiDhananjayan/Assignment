##Title
GermanyisCalling App Login Page Automation
##Description
This project focuses on automating the login page of the web application 'Germany is Calling'.It covers both successful and unsuccessfull login.

##Test Implentation
Login with valid credentials:Takes the user to thecorrect landing page after entering correct credentials.

Login with invalid credentials:An error message is displayed when the user is trying to login wuth incorrect credentials.

##Running the Test
1.Install jdk 8 or above 2.Create a maven project 3.Add the required dependencies to pom.xml 4.Execute the test using mvn test

##Assumption
The error message for unsuccessful login attempts is predefined and consistent The user interface including layout and element remains unchanged throughout the test execution The format and content of credentials such as userame/emailid and password are consistent

##Challenges
When automating the website a pop up is appearing and that is blocking the automation flow.Can't handle that popup because its not showing when manually handling the website
Some selectors might change if updated the website Network issues can affect the results if the website is not reachable
