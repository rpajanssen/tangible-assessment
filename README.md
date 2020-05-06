# ABNAMRO Assessment
Introduction
-
This assessment consists of 4 assignments.
Each assignment focuses on different aspects of Java programming, aspects common in corporate environments.

> Important: There is no wrong or right. Many different paths lead to success!

Assignment 1 - Create a Service (20 mins)
=
The person service obtains persons from the database (for demo/test purposes it might be best to configure an in memory database).
The service provides two services/methods:
* Create a person
* Get filtered persons

Create a person
-
All Persons require a name with at least 2 characters and a birthdate.
Duplicate person names are **not** allowed, throw an exception that explains what the problem is.
When a person does not meet the requirements, throw an exception that explains what the violations are.

Get filtered persons
-
Return only persons that are **not** born in the banned years (see banned-years file).

Before you start
- use GitPod : to open your GitHub repository in GitPod add https://gitpod.io/#  in front of the repository
  url (e.g. https://gitpod.io/#https://github.com/mygithib/my-demo)
- [F1] is the most **important** key in the online IDE
- Set the timer before **each** assignment: [F1] > start timer
-

General remarks
=
This assignment is about the following aspects:
- set up and implement a service
- validation
- error handling
- testing

These aspects could be topic of discussion during the interview.

Assignment 2 - Create Springboot web application (15 mins)
-
Use the previous service and create a restful endpoint to expose the service. You need to implement
two REST services:
- create person
- get filtered persons

This assignment is about the following aspects:
- set up and implement a rest api
- validation
- error handling
- testing

Assignment 3 - Create a commandline client to invoke the endpoints (15 mins)
-
This assignment is about the following aspects:
- Choice of framework, (e.g. spring-boot commandline-runner, or any other)
- calling a rest api

Assignment 4 - Create another restful web-application (20 mins)
-
This web application should also invoke the rest endpoints from assignment 2.
(If assignment 3 is not accompished, this assignment can still be made)

This assignment is about the following aspects:
- resilience / fault tolerance
- traceability
- context propagation
- service discovery
