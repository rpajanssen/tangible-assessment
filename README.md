# ABNAMRO Assessment
Introduction
-
This assessment consists of 4 assignments.
Each assignment focuses on different aspects of Java programming, aspects common in corporate environments.

> Important: There is no wrong or right. Many different paths lead to success!

Assignment 1 - Create Service
=
The person service obtains persons from the database (h2).
It provides two services/methods
* Create Person
* Get Filtered Persons

Create Person
-
ALL Persons require a name with at least 2 characters and a birthdate.
Duplicate Person names are **not** allowed, throw a BusinessException with a clear and simpel message.  
When a Person does not meet the requirement, throw an exception with a message indicating the issue(s).

Get Filtered Persons
-
Return only Persons which are **not** born in the banned years (see banned-years file).

General remarks
=
bla bla...   
@ALL, this assignment is about the following aspects:
- implement validation
- error handling
- lambda
- testing

these aspects could be topic of discussion during interview.

Assignment 2 - Create spingboot web application
-
Use the previous PersonService and create a web restful endpoints.   
aspects
- rest api
- error handling
- (testing)

Assignment 3 - Create a commandline client to invoke the endpoints
-
aspects   
- Choice of framework, (e.g. spring-boot commandline-runner, or any other)
- reuse code already made in previous assignments
- use of thirdparty libraries

Assignment 4 - Create another restful web-application
-
This web application should also invoke the rest endpoints from assignment 2.   
(If assignment 3 is not accompished, this assignment can still be made)

Microservices aspects   
- Fault Tolerance
- Context propogation
- Docker / Kubernetes ?