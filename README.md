## [Table of Contents](#table-of-contents)

1) [Concept](#concept)
2) [Wire-Frames (DRAFT)](#wire-frames)
3) [Database Diagram](#database-diagram)
4) [Entity Relationship Diagram (ERD)](#entity-relationship-diagram)
5) [User Stories](#user-stories)
6) [Use Cases](#use-cases)
7) [Use Case Diagram](#use-case-diagram)
8) [Requirements](#requirements)
9) [Requirements Table](#requirements-table)
10) [Test Case Table](#test-case-table)
11) [Prototype](#prototype)


## <div align="center">Concept</div>

A social media app where users can post small jobs that can be accepted by other user to do to get quick cash.

## <div align="center">Wire-Frames</div>
![First](https://github.com/MurdockTHS/Builders-App/blob/master/builder1.PNG)
![second](https://github.com/MurdockTHS/Builders-App/blob/master/builder2.PNG)
![third](https://github.com/MurdockTHS/Builders-App/blob/master/builder2.PNG)

## <div align="center">Database Diagram</div>
Currently being updated

## <div align="center">Entity Relationship Diagram</div>

![first](https://github.com/MurdockTHS/Builders-App/blob/master/builderedr.PNG)

## <div align="center">User Stories</div>
**1.** As a user, I need to login or register for an account.

**2.** As a user, I need to post my content for others to see.

**3.** As a user, I need to see the the link attached to the post.

**4.** As an administrator, I need to be able to grant users permissons when requested.

## <div align="center">Use Case Diagram</div>

* Use Case Scenarios
* Given that a user has a profile with the app
* When they attempt to login
* Then the action should be completed with no errors

* Given a user has a project they want to share
* When they attempt to upload the photo
* Then they should be given the options to share it with their friends or a community

* Given a user forgets their password
* When they attempt to log in there is a forgot password hyperlink
* Then the hyperlink will send a change password link to their email

* Given a users want to ask more about a photo that another user posted
* When looking at the photo the user can scroll down to see a comment section
* Then a user can click on it to leave a comment.

## <div align="center">Use Case Diagram</div>
![first](https://github.com/MurdockTHS/Builders-App/blob/master/FirstDraftUMP.PNG)

# <div align="center">Requirements</div>

* 1.0\. System shall request users to log in to enter the website.
   * 1.1.0\. System shall verify users input for Username and Password.
    * 1.1.1\. System shall display error message if the Username and Password does not match the database. 
    * 1.1.2\. System shall allow user to reset their password through their email if they have forgotten.

* 2.0\. User shall be able to swipe through the featured roasted coffee beans on the featured page.
   * 2.1.0\. User shall be able to scroll through all featured coffee beans from the last year.
   * 2.1.0\. User shall be able to select the featured roast from the featured page and add it to their cart.

* 3.0\. User shall be able to select the links to the parts that are on the post.

* 4.0\. User shall be able to follow other users.
   * 4.1.0\. User shall be able to follow communities.
   * 4.2.0\. User shall be able to leave the application and upon relogging in their cart will still be the same as when they left the application.

## <div align="center">Requirements Table</div>

| Requirement ID 	| Requirement Description                                                                                                                                      	| Test Method   	| Test ID 	|
|----------------	|--------------------------------------------------------------------------------------------------------------------------------------------------------------	|---------------	|---------	|
| 1.0            	| System shall request users log in to enter the website | inspection    	| TC1   	|
| 1.1.0          	| System shall verify users input for Username and Password. | Test | TC1   	|
| 1.1.1          	| System shall display error message if the Username and Password does not match the database. | Demonstration	| TC2   	|
| 1.1.2          	| System shall allow user to reset their password through their email if they have forgotten. | Demonstration 	| TC2   	|
| 2.0            	| User shall be able to look through a feed with post of there followings.| not tested 	| Demonstration   	|
| 2.1          	| User shall be able to select the top posts.                                         | Demonstration 	| TC3  |
| 3.0            	| User shall be able to select the links to the parts that are on the post. | Inspection 	| TC4   	|
| 4.0            	| User shall be able to follow other users.| Demonstration 	| TC5   	|
| 4.1.0          	| User shall be able to follow communities. | Test 	| TC6   	|
| 4.2.0          	| User shall be able to leave the application and upon relogging in their cart will still be the same as when they left the application. | Inspection | TC6 |


## <div align="center">Test Case Table</div>


| Test ID 	| Req. ID            	| Test Procedure                                                                                                 	| Current Status 	| Time Stamp 	|
|---------	|--------------------	|----------------------------------------------------------------------------------------------------------------	|----------------	|------------	|
| TC1   	| 1.0, 1.1.0         	| System shall request and verify username and password for log in                                               	| not tested     	|           |
| TC2   	| 1.1.1, 1.1.2       	| Display error message if the username and password in incorrect, send an email to reset username and password. 	| not tested     	|           |
| TC3   	| 2.0, 2.1 2.2   	| User should be able to see a home feed.                      	| not tested     	|            	|
| TC4   	| 3.0,        	| The links should take the user to the proper link and the link parts included in post.      	| not tested     	|            	|
| TC6   	| 4.1.0, 4.2.0 	| Users should be reflective of their selections including after they leave the website and return.          	| not tested    	|            	|


## <div align="center">Prototype</div>
![First](https://github.com/MurdockTHS/Builders-App/blob/master/prototype.PNG)
