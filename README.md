# CS420Midterm

Build a web based bug reporting system. This system will be used by a software development
company in the software quality assurance process.

 Part 1
 - [x] Download the SQLServer Express database (zip file) from Canvas. This database contains user information and bug information.

  Part 2
- There are 4 types of users: Tester, Manager, Developer, and Administrator. 
 - [x] Create webform for Developer, Tester, Manager, and Administrator.
 - [x] Testers enter new bugs into the database.
 - [x] Managers assign newly reported bugs to Developers. 
 - [x] Developers fix the bugs that were assigned to them. 
 - [x]Administrators are allowed to create new users.
 - [x]The EnteredBy field will contain the UserID of the Tester who entered the bug. 
 - [x] The AssignedTo field will contain the UserID of the Developer who is assigned by the Manager to fix this bug. 
 - [x]The Priority can be High or Medium or Low in a drop down menu. 
 - [x]Status function 
   - [x]Stauts is set to Open when a new bug is entered 
   - [x]Status is set to Assigned when a Manager assigns a bug to a Developer
   - [x] Status is set to Completed when a Developer fixes a bug

Part 3
- [x] The users will be presented with a login screen.
 - [x] Create login screen
- [x] If a user is authenticated, the browser loads one of the four corresponding web pages depending on the user type. 
  User passwords are stored as SHA-1 hash values. Currently, the password for all users is set to ballstate0. You may use http://www.miraclesalad.com/webtools/sha1.php to generate and store passwords for users. 
- [x] A Tester should be allowed to enter all the relevant information for a new bug (see fields in the table). 
 - [x]The bug number is automatically generated (incremented by 1 each time). 
 - [x] When the Tester clicks the Submit button, the bug is added to the database.

Part 4
- [x] When a Manager logs in, he/she is presented with a list of bugs in a drop down list. 
- [x]Another dropdown list should be populated with the names of Developers. 
- [x] The Manager should be able to look at all the relevant information about a bug. 
- [x]The Manager should be able to assign the selected bug to a specific Developer and the database should be updated accordingly.

Part 5
- [x] When a Developer logs in, he/she is presented with a list of bugs assigned to him/her. 
- [x] The Developer (assume that he/she fixes the bugs) reports the steps that were taken to resolve the bug and clicks on the Fixed button. 
- [x] When the developer clicks the Fixed button, the database should be updated accordingly.

Part 6
- [x] When an Administrator logs in, he/she is presented with a screen to add a new user. 
- [x] UserID for the new user should be the next available UserID. The username of the new user should be unique. 
- [x] The password must be at least 8 characters long and must contain at least one letter and at least one number.
