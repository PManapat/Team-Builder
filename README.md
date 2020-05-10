# Unit 10 OOP Homework: Team Builder

## Author: PManapat

### Description 

This application allows the user to generate a team profile using Node.js, Inquirer and File System libraries to create a HTML webpage.


### Instructions

The User will be prompted with the following command line questions:

* Team member's name.
* Team member's role.
* Team member's ID.

Depending on the team member's role, the user will be prompted with the following for each role accordingly:

* Role - Manager: Office phone number.
* Role - Engineer: Github username.
* Role - Intern: School name.

After retrieving the data for each team member, the user will be prompt if the user would like to add more team members. If the user selects "no" The user will be prompted with "Finished, Your Team Profile is ready. 

### Installation
```
Once inside the Develop folder:
npm install
node app.js
```
### Demo

![Team Builder Demo](demo.gif)

![Team Builder HTML](demo.png)

### Test

Jest Tested - located in the `test` directory


