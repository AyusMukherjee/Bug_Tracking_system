# Bug_Tracking_system 
What is Bug tracking system? 

A bug tracking system is software that keeps track of bugs that the user encountered in any software development or in any project.Bug Tracking System must be in place for every infrastructure we design. Software is no exception to this. This application which will be implemented on Java platform is designed to track the status of bugs that are reported during Software testing.


The three main functionalities of the Bug Tracking system is:

Creating a new text file and writing the details entered by the user into the text file.
Option to change the status of the bug.
Report of specific bug file.



Existing system

The bugs that are identified by tester in software testing phase are reported to Project Manager and developer through simple shared lists and emails. Most of the companies share this information through document called “Defect report”. This procedure is error prone and there is ample chance of leaving some bugs unfixed and ignored as there is no particular tracking system in place. The team involved in the software development life cycle must be aware of the status of each and every bug reported.  The existing system fails to fulfill this requirement thus it affects productivity and accountability of every member of team.



Proposed system

Bug tracking system is essentially and effectively implemented to monitor the status of bugs in an application. All the bugs that are identified are stored in a database. Each bug is assigned with an unique bug id and respective status of bug. Bugs can be created and updated with ease. Specific user accounts to control the access and maintain security are incorporated into the application.Bug tracking system which is implemented on Java provides an overview on standards of coding of the developers involved. Employee accountability can be tracked and analyzed on daily basis by using report generation option.



Now will see what are functions involved :


Driver Function: The idea is to keep a variable id that stores the id of the Bugs that are registered till now. There are mainly three options out of which user can select the functionality:

Create New Bug
Change Status of Bug
Report a Bug
Exit



Create a New Bug: This function will ask the user for his name, and create a new text file as a name with the id number attached to it.

For Example:

If the user creating a bug file for the first time id which is initially 0 incremented by 1 and if the user enters name as bugfile then the file that our program will create will be named as bugfile1.txt 
If the user creating a bug file for the 3rd time id incremented by 1 three times and if the user enters the name as bugfile again then the file that our program will create will be named as bugfile3.txt
After naming the file, Take the information from the user and add it to the text file with the time of creation attached to it 

The information is taken by a user for a bug is:

Bug Filed by User.
Bug Type
Bug Priority
Bug Description
Bug Status


Change Status of Bug: Take the information about the bug and change the status of the bug in the desired file. Also, update the Last Updated Time of the Bug.

Report a Bug: Take the information about the bug. Such as Bug file name and print the contents of the Bug.
