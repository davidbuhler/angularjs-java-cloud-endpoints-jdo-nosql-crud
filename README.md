### Knacked Up! An Open Source Application

#####Trade 8 hours of work for a Recommendation or Guidance

## Website
https://knackedupapp.appspot.com
 
## Motto
Get hooked up with 8 hours of work and turn a hobby into a career.

## What is it?
It's a Craigslist for college students, interns, and entry-level professionals, and an open-source project. You're free to fork the code base, build your own project, or contribute to this project with thoughts or ideas.

## Stack
* AngularJS (1.x)
* Java
* Google App Engine
* Google Document Search
* Google Cloud Endpoints / REST
* Google Authentication
* Google's Mail Services
* JDO/JPA
* Hibernate Validation
* Maven
* Twitter Bootstrap
* Toastr

## Setup
1. Import the project into Eclipse.
2. Make sure the App Engine SDK jars are added to the war/WEB-INF/lib directory, either by adding them by hand, or having Eclipse do it. (An easy) way to do this in Eclipse is to unset and reset whether or not the project uses Google App Engine.
3. Update the value of application in appengine-web.xml to the app ID you have registered in the App Engine admin console and would like to use to host your instance of this sample.
4. Update the values in "Ids.java" to reflect the respective client IDs you have registered in the APIs Console.
5. Either enable Maven's dependency management, or force the Maven pom to update snapshots.
6. Update the value of CLIENT_ID to reflect the web client ID you have registered in the APIs Console.
7. Run the application, and ensure it's running by visiting your local server's address (by default localhost:8888.)
8. Deploy your application.

### Backstory
Before David Buhler got into programming, he went to lots of interviews. He went door to door, passing out resumes. After a series of bad interviews, he asked the interviewer why she wouldn't hire him, and she was nice enough to give some helpful advice. David left the interview, walked to the bookstore across the street, bought a book on how to interview, and got a job the very next day. There's value in asking and receiving feedback.

### Licensing
The source code is provided to you using an Apache License.
